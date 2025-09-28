# ProyecRomance

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/NamaLo/ProyecRomance)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> A decentralized, privacy-focused browser built on a custom protocol. Reclaiming the internet, one line of code at a time.

ProyecRomance isn't just a browser; it's an exploration into digital sovereignty. In a world dominated by centralized platforms, this project is a statement—a romance with the pure, untamed potential of a truly private web.

## Core Philosophy

- **Absolute Privacy:** No trackers, no telemetry, no compromises. Your data is yours alone.
- **Decentralized by Design:** Built on a custom protocol (`blabla://`) and a user-defined naming system.
- **Open & Transparent:** Every line of code is open for scrutiny. This is security through transparency, not obscurity.
- **Developer-First:** Built by a purist, for purists.

## High-Level Architecture

Here's a simplified look at how the ecosystem is designed to work:

```
+-------------------+      +---------------------+      +-------------------+
|                   |      |                     |      |                   |
|  ProyecRomance    |      |    Naming Server    |      |   blabla://       |
|  (Client APK)     |<---->|  (Private DNS)      |<---->|   (Content Server)|
|                   |      |                     |      |                   |
+-------------------+      +---------------------+      +-------------------+
       ^                                                        ^
       |                                                        |
       +------------------- blabla:// protocol -----------------+
```

## Roadmap

- [ ] **Phase 1: The Core Protocol** - Define and implement the `blabla://` protocol.
- [ ] **Phase 2: The Terminal Proof-of-Concept** - Build a working server and terminal-based client.
- [ ] **Phase 3: The Android APK** - Develop the GUI client using Kivy and compile the first APK.
- [ ] **Phase 4: The Naming System** - Implement the first version of the private naming server.

## Getting Started

> Instructions for contributors will be added here soon.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
