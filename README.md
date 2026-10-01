<p align="center"><img src="media/intro.gif" alt="Lumo intro" width="720"></p>

<h3 align="center">Lumo — a private home cinema controlled from Discord and the web</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/discord.py-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="discord.py">
  <img src="https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white" alt="FFmpeg">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

> **Source code is private.** This repository is a short project showcase.

## What it is

Lumo turns my home PC into a small private cinema for me and a few friends. Films, series and YouTube can be started from a Discord panel, from a web app on any device, or by voice. Friends can also watch a film together online in a virtual cinema hall.

## Highlights

- **Discord control panel**: everything is done with buttons, no commands.
- **Web app** with Discord login and a custom video player (HLS).
- **Cinema hall**: synced playback for everyone, chat, and each viewer picks their own quality.
- **Voice control**: works offline with faster-whisper.
- **Runs 24/7** with a watchdog and automatic restart.

About 20,000 lines of code in Python and JavaScript.

## Screenshots

| Home | Catalog |
|---|---|
| ![Home](media/home.png) | ![Catalog](media/movies.png) |
| **Cinema hall** | **Host controls** |
| ![Cinema hall](media/sal-viewer.jpg) | ![Host controls](media/sal-host.jpg) |

## Tech

Python · asyncio · discord.py · aiohttp · FFmpeg (GPU) · HLS · JavaScript · WebSockets

---

All rights reserved. Built with AI-assisted development (Claude Code).
