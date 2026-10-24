<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <img src="assets/hero-light.svg" alt="Arel Kair" width="380">
</picture>

I'm Arel, a developer from Spain who builds with AI: agents, automations, web projects, and games. My work falls into three areas:

- **Low-level engineering.** Translating console games into native PC programs through static recompilation, with no emulator in the way.
- **Privacy-first web apps.** Software that keeps your data on your own device, with no account and no tracking.
- **Browser games.** Multiplayer games that run peer-to-peer, so there is nothing to host and nothing to install.

[![Website](https://img.shields.io/badge/arelkair.dev-1B4332?style=flat-square&logo=googlechrome&logoColor=F3EEE4)](https://arelkair.dev)
[![Followers](https://img.shields.io/github/followers/arelkair?style=flat-square&label=followers&labelColor=1B4332&color=2F7D57&logo=github&logoColor=F3EEE4)](https://github.com/arelkair?tab=followers)
[![Location](https://img.shields.io/badge/based_in-Spain-1B4332?style=flat-square&logoColor=F3EEE4)](https://arelkair.dev)

## Featured projects

<img align="right" width="300" src="https://raw.githubusercontent.com/arelkair/wiiparty-recomp/main/docs/progress.svg" alt="Wii Party Recomp progress by component">

### [Wii Party Recomp](https://github.com/arelkair/wiiparty-recomp)

![Status](https://img.shields.io/badge/status-alpha_93%25-1B4332?style=flat-square&labelColor=1B4332&color=2F7D57)
![Stars](https://img.shields.io/github/stars/arelkair/wiiparty-recomp?style=flat-square&labelColor=1B4332&color=2F7D57&logo=github&logoColor=F3EEE4)
![License](https://img.shields.io/github/license/arelkair/wiiparty-recomp?style=flat-square&labelColor=1B4332&color=2F7D57)

Static recompilation of Wii Party for native PC. The game's PowerPC code is translated into C++ and compiled into a Windows or Linux program, while the console hardware (GPU, DSP audio, Bluetooth, disc and NAND) is reimplemented underneath.

- Plays complete Board Game Island sessions and every Free Play minigame.
- Runs at a locked 60 fps at up to 6x the console's resolution.
- The toolchain is checked by 4,152 tests against an independent model.
- No game files are distributed: it builds from your own copy of the disc.

![C++](https://img.shields.io/badge/C++-1B4332?style=flat-square&logo=cplusplus&logoColor=F3EEE4)
![Python](https://img.shields.io/badge/Python-1B4332?style=flat-square&logo=python&logoColor=F3EEE4)
![CMake](https://img.shields.io/badge/CMake-1B4332?style=flat-square&logo=cmake&logoColor=F3EEE4)
![Direct3D](https://img.shields.io/badge/D3D11-1B4332?style=flat-square&logo=windows11&logoColor=F3EEE4)

<br clear="right">

<img align="right" width="300" src="https://raw.githubusercontent.com/arelkair/home/main/src/assets/work/nivra.jpg" alt="Nivra dashboard">

### [Nivra](https://nivra.arelkair.dev)

[![Live](https://img.shields.io/badge/app-live-1B4332?style=flat-square&labelColor=1B4332&color=2F7D57)](https://nivra.arelkair.dev)
![Stack](https://img.shields.io/badge/local--first-no_account-1B4332?style=flat-square&labelColor=1B4332&color=2F7D57)

A privacy-first personal organizer for the browser. Calendar, timetable, tasks, exams, grades, notes and personal finances, all stored on your own device.

- Two interfaces over the same data: the classic dashboard and Initiative, a minimalist redesign.
- A notes vault with wikilinks, backlinks, an interactive graph and Obsidian import.
- A built-in laboratory: scientific calculator, image converter and PDF tools that process files in the browser and never upload them.

![TypeScript](https://img.shields.io/badge/TypeScript-1B4332?style=flat-square&logo=typescript&logoColor=F3EEE4)
![React](https://img.shields.io/badge/React-1B4332?style=flat-square&logo=react&logoColor=F3EEE4)
![Vite](https://img.shields.io/badge/Vite-1B4332?style=flat-square&logo=vite&logoColor=F3EEE4)

<br clear="right">

<img align="right" width="300" src="https://raw.githubusercontent.com/arelkair/home/main/src/assets/work/pool.jpg" alt="Pool gameplay">

### [Pool](https://github.com/arelkair/pool)

[![Play](https://img.shields.io/badge/play-live_demo-1B4332?style=flat-square&labelColor=1B4332&color=2F7D57)](https://pool.arelkair.dev)
![License](https://img.shields.io/github/license/arelkair/pool?style=flat-square&labelColor=1B4332&color=2F7D57)

2D 8-ball for the browser with online 1v1. One player creates a game and shares a 4-letter code, the other joins with it, and the match runs peer-to-peer with no servers or router setup.

- A custom billiards physics engine: collisions, friction and pockets.
- Standard 8-ball turn rules, in English and Spanish.

![JavaScript](https://img.shields.io/badge/JavaScript-1B4332?style=flat-square&logo=javascript&logoColor=F3EEE4)
![PixiJS](https://img.shields.io/badge/PixiJS-1B4332?style=flat-square&logo=pixijs&logoColor=F3EEE4)
![WebRTC](https://img.shields.io/badge/PeerJS-1B4332?style=flat-square&logo=webrtc&logoColor=F3EEE4)

<br clear="right">

<img align="right" width="300" src="https://raw.githubusercontent.com/arelkair/home/main/src/assets/work/candy-board.jpg" alt="Poisoned Candy board">

### [Poisoned Candy](https://github.com/arelkair/poisoned-candy)

[![Play](https://img.shields.io/badge/play-live_demo-1B4332?style=flat-square&labelColor=1B4332&color=2F7D57)](https://candy-arelkair.vercel.app)
![Players](https://img.shields.io/badge/players-2_to_5-1B4332?style=flat-square&labelColor=1B4332&color=2F7D57)

A multiplayer board game. Players secretly choose which tiles hold poisoned candy, then take turns eating from the board. Pick a poisoned one and you lose a life. Between rounds you can buy wildcards with special effects.

- Local on one device, or online through rooms with an invite code.
- Every room is configurable: board size, lives, timers, wildcards and candy skins.
- Plain HTML, CSS and JavaScript, with no frameworks and no build step.

![JavaScript](https://img.shields.io/badge/JavaScript-1B4332?style=flat-square&logo=javascript&logoColor=F3EEE4)
![HTML5](https://img.shields.io/badge/HTML5-1B4332?style=flat-square&logo=html5&logoColor=F3EEE4)
![CSS3](https://img.shields.io/badge/CSS3-1B4332?style=flat-square&logo=css3&logoColor=F3EEE4)

<br clear="right">

## Tech stack

**Languages**

![C++](https://img.shields.io/badge/C++-1B4332?style=flat-square&logo=cplusplus&logoColor=F3EEE4)
![C#](https://img.shields.io/badge/C%23-1B4332?style=flat-square&logo=csharp&logoColor=F3EEE4)
![TypeScript](https://img.shields.io/badge/TypeScript-1B4332?style=flat-square&logo=typescript&logoColor=F3EEE4)
![JavaScript](https://img.shields.io/badge/JavaScript-1B4332?style=flat-square&logo=javascript&logoColor=F3EEE4)
![Python](https://img.shields.io/badge/Python-1B4332?style=flat-square&logo=python&logoColor=F3EEE4)
![HTML5](https://img.shields.io/badge/HTML5-1B4332?style=flat-square&logo=html5&logoColor=F3EEE4)
![CSS3](https://img.shields.io/badge/CSS3-1B4332?style=flat-square&logo=css3&logoColor=F3EEE4)

**Frameworks and libraries**

![React](https://img.shields.io/badge/React-1B4332?style=flat-square&logo=react&logoColor=F3EEE4)
![Vite](https://img.shields.io/badge/Vite-1B4332?style=flat-square&logo=vite&logoColor=F3EEE4)
![PixiJS](https://img.shields.io/badge/PixiJS-1B4332?style=flat-square&logo=pixijs&logoColor=F3EEE4)
![PeerJS](https://img.shields.io/badge/PeerJS-1B4332?style=flat-square&logo=webrtc&logoColor=F3EEE4)

**Tools**

![Node.js](https://img.shields.io/badge/Node.js-1B4332?style=flat-square&logo=nodedotjs&logoColor=F3EEE4)
![CMake](https://img.shields.io/badge/CMake-1B4332?style=flat-square&logo=cmake&logoColor=F3EEE4)
![Git](https://img.shields.io/badge/Git-1B4332?style=flat-square&logo=git&logoColor=F3EEE4)
![GitHub](https://img.shields.io/badge/GitHub-1B4332?style=flat-square&logo=github&logoColor=F3EEE4)
![Vercel](https://img.shields.io/badge/Vercel-1B4332?style=flat-square&logo=vercel&logoColor=F3EEE4)
![VS Code](https://img.shields.io/badge/VS_Code-1B4332?style=flat-square&logo=visualstudiocode&logoColor=F3EEE4)

## Portfolio

My site, [arelkair.dev](https://arelkair.dev), has a case study for each project above, with real screenshots. It is plain HTML, CSS and JavaScript and is available in English, Spanish, Korean and Mandarin Chinese, in light and dark themes. The source is in [arelkair/home](https://github.com/arelkair/home).

## Find me

[![Website](https://img.shields.io/badge/Website-1B4332?style=flat-square&logo=googlechrome&logoColor=F3EEE4)](https://arelkair.dev)
[![X](https://img.shields.io/badge/X-1B4332?style=flat-square&logo=x&logoColor=F3EEE4)](https://x.com/arelkair)
[![YouTube](https://img.shields.io/badge/YouTube-1B4332?style=flat-square&logo=youtube&logoColor=F3EEE4)](https://www.youtube.com/@arelkair)
[![TikTok](https://img.shields.io/badge/TikTok-1B4332?style=flat-square&logo=tiktok&logoColor=F3EEE4)](https://www.tiktok.com/@arelkair)
[![Discord](https://img.shields.io/badge/Discord-1B4332?style=flat-square&logo=discord&logoColor=F3EEE4)](https://discord.com/users/1505398694810357830)
