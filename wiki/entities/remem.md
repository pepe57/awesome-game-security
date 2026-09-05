---
title: remem
kind: entity
topics: [game-hacking, reverse-engineering]
sources:
  - wiki/sources/descriptions/0xenia__remem.md
updated: 2026-09-05
confidence: medium
---

# remem

Header-only **C++ memory manipulation library** for Windows applications (0xenia). Provides typed read/write helpers with **pointer validation**, optional exception handling, and optional logging to reduce unsafe cross-process access failures. Includes **pattern scanning** utilities and wrappers for calling remote functions with common calling conventions. Useful for reverse engineering tools, game memory research, and other low-level debugging tasks. README tag: **RPM for Windows**. (source: wiki/sources/descriptions/0xenia__remem.md)

Sits in the lightweight usermode RPM library lane beside [[libmem]], [[blackbone]], and [[umpmlib]] when building external tools that need typed helpers and scan primitives without a full process-manipulation framework.

## Links

- Repo: https://github.com/0xenia/remem

## Related

[[libmem]] · [[blackbone]] · [[umpmlib]] · [[creadmemory]] · [[shirakumo]] · [[overviews/game-hacking]] · [[overviews/reverse-engineering]]
