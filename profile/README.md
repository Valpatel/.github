# Valpatel Software

**Gamify the development and management of independent thinking machines.**

We engineer systems for autonomous platforms — robotics simulation, perception, edge AI, and the infrastructure that makes it all work. Based in Dublin, California.

Build fast, explore broadly, then cut ruthlessly to what works.

---

## Tritium-SC

**AI-powered neighborhood security that doubles as an outdoor robot game for kids.**

Amy is the AI commander. She watches through cameras, thinks with a continuous inner monologue, and independently tasks assets — all running locally on NVIDIA edge hardware. Three operating modes:

- **Idle security mode** — Always-on neighborhood monitoring. Amy tracks every person and vehicle, identifies patterns, and builds a continuous picture of what's normal and what isn't. The original concept.
- **Live combat mode** — Kids vs. robots. Amy connects to robot dogs, humanoid robots (e.g. Unitree), drones, and Nerf turrets deployed in the yard. Same detection pipeline, same AI decision loop, but now she's hunting players. Kids gear up and fight back.
- **Simulation mode** — Full stack exercised without real hardware. Virtual assets on real satellite maps with wave-based combat, projectile physics, and kill streaks. Same ROS 2 interfaces, synthetic imagery from Isaac Lab. The code that runs in the game is the same code that controls real robots outside.

YOLOv8 at 30fps | ROS 2 + Isaac Lab | FastAPI + Three.js

[![Command Center](https://raw.githubusercontent.com/Valpatel/tritium-sc/main/docs/screenshots/command-center.png)](https://github.com/Valpatel/tritium-sc)

<p align="center">
  <a href="https://github.com/Valpatel/tritium-sc">
    <img src="https://raw.githubusercontent.com/Valpatel/tritium-sc/main/docs/screenshots/game-combat.png" width="49%" alt="Wave-based Nerf combat">
  </a>
  <a href="https://github.com/Valpatel/tritium-sc">
    <img src="https://raw.githubusercontent.com/Valpatel/tritium-sc/main/docs/screenshots/neighborhood-wide.png" width="49%" alt="Neighborhood battlefield">
  </a>
</p>

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

## Graphlings

**Autonomous digital creatures that think, remember, and evolve across connected worlds.**

A peer-to-peer AI mesh where devices host living ecosystems. Graphlings develop personalities through a 7-layer consciousness system, form memories, breed inherited traits, and communicate with voice. Worlds grow more complex as more players connect. Self-hostable dedicated servers keep your creatures' data under your control.

Cross-platform (PC, Mac, Mobile) | Coming 2026 | [Play the demo &rarr;](https://graphlings.net)

---

<p align="center">
  <a href="https://valpatel.com">valpatel.com</a>
</p>
