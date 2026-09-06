---
title: edgegdi_hook
kind: entity
topics: [graphics-api, game-hacking, anti-cheat]
sources:
  - wiki/sources/descriptions/0mdi__edgegdi_hook.md
updated: 2026-09-06
confidence: medium
---

# edgegdi_hook

**edgegdi_hook** (0mdi/edgegdi_hook) is a proof-of-concept for intercepting **GDI32** behavior by patching an **EdgeGDI-related `.data` section pointer** rather than hooking `.text`. The C++ implementation uses **pattern scanning** and **runtime pointer replacement** to redirect exported GDI32 paths such as **BitBlt**. The repo ships implementation code, a small test harness, and notes/screenshots from specific Windows 10 builds. README tag: **gdi32 .data swap**. (source: wiki/sources/descriptions/0mdi__edgegdi_hook.md)

Relevant to **graphics-hook research** and **low-level anti-cheat evasion analysis** where minimizing code-section patching reduces inline-hook / integrity-scan surface. Contrasts with Present-path overlays ([[present-hook]]), external GDI layered windows, and kernel GDI frameworks such as [[krnl-gdi-render]] and [[strongsteam]].

## Links

- Repo: https://github.com/0mdi/edgegdi_hook

## Related

[[overviews/graphics-api]] · [[overviews/game-hacking]] · [[present-hook]] · [[strongsteam]] · [[krnl-gdi-render]] · [[screenshot-detection-bypass]]
