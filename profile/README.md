# Valpatel Software

**Gamify the development and management of independent thinking machines.**

We engineer systems for autonomous platforms — robotics simulation, perception, edge AI, and the infrastructure that makes it all work. Based in Dublin, California.

Build fast, explore broadly, then cut ruthlessly to what works.

---

## <img src="https://raw.githubusercontent.com/mvalancy/mvalancy/main/graphlings-logo.png" width="32" alt=""> [Graphlings](https://graphlings.net)

*[Graphlings](https://graphlings.net) — Created by Matthew Valancy, Copyright 2026 Valpatel Software LLC.*

**Persistent crystal creatures that live, think, and remember across connected worlds.**

[Graphlings](https://graphlings.net) are autonomous digital life forms — crystal creatures with personalities, memories, and motivations that develop over time in their own game universe. They aren't scripted NPCs. Each one runs on a local LLM, observes its surroundings, reasons about what to do, and acts independently. They form relationships, remember experiences, breed inherited traits, and communicate with voice.

When a simulation begins in another system (like [Tritium-SC](#tritium-sc)), Graphlings cross over from their home world to play roles — a defender who remembers last week's breach, an attacker with a grudge, a bystander who notices things. When the mission ends, they return home with new memories. Think of it like the TV show *ReBoot*: the simulation is a game that descends into the Graphlings' world. They suit up, play their parts, and go home when the game ends.

The system distributes Graphling cognition across your local compute fleet — desktop mini PCs, RTX workstations, NVIDIA Jetson, Mac Minis, or any Ollama-capable device on your network or Tailscale mesh. Small fast models handle background life; larger models drive critical decisions. Community ownership means your AI runs on your hardware. Self-hostable dedicated servers keep your creatures' data under your control.

Cross-platform (PC, Mac, Mobile) | Coming 2026 | [graphlings.net &rarr;](https://graphlings.net)

---

## [Tritium](https://github.com/Valpatel/tritium) — Unified Operating Picture

**Neighborhood security is too important to be a SaaS.** Track, identify, and fuse every target — BLE, WiFi, camera, radar, SDR, LoRa mesh, acoustic — into one tactical picture on a real-world map. Runs entirely on your own hardware.

Every detected entity gets a unique target ID. A BLE scanner sees a phone. A camera sees a person. TPMS picks up tire sensors from a car. The system correlates them into one entity and builds a dossier that grows over time — daily routines, travel routes, known associates.

- **23+ sensor plugins** — BLE tracking, WiFi fingerprinting, YOLO detection, license plate recognition, acoustic classification, SDR spectrum monitoring, LoRa mesh, ATAK/CoT interoperability
- **Pluggable AI commander** — monitors the tactical picture, narrates events, dispatches assets. Runs on local LLMs via Ollama
- **Edge firmware** — Tritium-OS for ESP32-S3 with 66+ HALs (BLE, WiFi, acoustic, LoRa, power management)
- **Self-improving** — 92% accurate target correlator via reinforcement learning. 933-entry BLE device database. Autonomous development loop with local LLM monitoring
- **Battle simulation** — same sensor fusion pipeline exercised with wave-based combat, projectile physics, and AI narration

**[Graphlings](https://graphlings.net) integration:** Tritium's plugin system deploys Graphlings from their home universe into battle scenarios as intelligent NPCs — autonomous agents that observe, reason, and remember. When the battle ends, they return home with new memories.

Three components: [**tritium-lib**](https://github.com/Valpatel/tritium-lib) (shared models + interfaces) | [**tritium-sc**](https://github.com/Valpatel/tritium-sc) (command center, port 8000) | [**tritium-edge**](https://github.com/Valpatel/tritium-edge) (ESP32 firmware + fleet server, port 8080)

Python 3.12 + FastAPI + vanilla JS | AGPL-3.0

[![Tritium Command Center](https://github.com/Valpatel/tritium/raw/dev/docs/screenshots/command-center.png)](https://github.com/Valpatel/tritium)

---

## Sound Box

**Synthetic audio generation for AI agents. Local GenAI SoundCloud for humans.**

A local, offline box that provides synthetic music, sound effects, and voice to any agent or app on your network. AI agents discover it automatically via MCP, generate and review assets, and pull audio programmatically — no human in the loop required. Multiple engines (MusicGen, AudioGen, MAGNeT, Piper TTS) running on local GPU. All output is CC0 public domain.

For humans, it's a full listening app — community radio stations, a searchable library, 10 real-time visualizers, voting, favorites, and fullscreen immersive mode. The UI makes it fun to browse and curate what the AI is producing.

Flask + PyTorch + SQLite FTS5 | Runs on desktop GPU, Jetson, or DGX

[![Sound Box Radio](https://raw.githubusercontent.com/Valpatel/app-soundbox/main/docs/screenshots/radio.png)](https://github.com/Valpatel/app-soundbox)

<p align="center">
  <a href="https://github.com/Valpatel/app-soundbox">
    <img src="https://raw.githubusercontent.com/Valpatel/app-soundbox/main/docs/screenshots/library.png" width="49%" alt="Library search">
  </a>
  <a href="https://github.com/Valpatel/app-soundbox">
    <img src="https://raw.githubusercontent.com/Valpatel/app-soundbox/main/docs/screenshots/visualizer.png" width="49%" alt="Visualizer">
  </a>
</p>

---

## CyberPower PDU Bridge

**Self-hosted monitoring and automation for CyberPower power distribution units.**

Real-time web dashboard for PDUs and automatic transfer switches. Polls devices over SNMP and serial, publishes metrics to MQTT, stores 60 days of 1Hz time-series data, and integrates with Home Assistant auto-discovery. Centralized control of multiple PDUs with an in-app automation rules engine.

Python + Docker + MQTT + InfluxDB | [github.com/mvalancy/CyberPower-PDU](https://github.com/mvalancy/CyberPower-PDU)

[![PDU Dashboard](https://github.com/mvalancy/CyberPower-PDU/raw/main/docs/screenshots/dashboard.png)](https://github.com/mvalancy/CyberPower-PDU)

---

<p align="center">
  <a href="https://valpatel.com">valpatel.com</a>
</p>
