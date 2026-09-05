---
title: MOABile
kind: entity
topics: [mobile-security, reverse-engineering, game-hacking]
sources:
  - wiki/sources/descriptions/jafarm189__MOABile.md
  - wiki/sources/README-categories.md
updated: 2026-09-05
confidence: medium
---

# MOABile

All-in-one mobile security toolkit that unifies professional testing utilities into a single text-based interface for assessing Android and iOS application security from a desktop computer. (source: wiki/sources/descriptions/jafarm189__MOABile.md)

## Capabilities

- **Multi-device** — simultaneous Android and iOS session management from one host
- **Connectivity** — ADB (Android); iproxy and ioscpy (iOS)
- **File transfer** — dual-pane host↔device copy
- **Screen mirror** — live display via [[scrcpy]]
- **Runtime inspection** — automated Frida and Objection setup for attach/spawn and app exploration
- **Interface** — Python TUI with arrow-key navigation and real-time status updates

Aimed at penetration testers, mobile security researchers, and developers who need an accessible way to perform authorized local security assessments on devices they own — including game clients probed via [[frida]] for SSL pinning, root checks, and in-memory hooks. (source: wiki/sources/descriptions/jafarm189__MOABile.md)

## Links

- Repo: https://github.com/jafarm189/MOABile (README `Cheat` / Frida)

## Related

[[overviews/mobile-security]] · [[overviews/game-hacking]] · [[overviews/reverse-engineering]] · [[frida]] · [[rootraven]] · [[mast-orchestrator]] · [[frida-ide]] · [[scrcpy]] · [[mobile-anti-cheat]]
