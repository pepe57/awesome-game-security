---
title: rhabdomancer
kind: entity
topics: [reverse-engineering, game-hacking]
sources:
  - wiki/sources/descriptions/0xdea__rhabdomancer.md
updated: 2026-09-06
confidence: medium
---

# rhabdomancer

**Rust-based binary auditing tool** implemented as a **headless IDA Pro plugin** (idalib). Locates call sites to potentially **insecure API functions** — e.g. `strcpy`, `sprintf`, `system`, `ioctl` — in compiled binaries to surface **candidate vulnerability points** for manual review. Features include **tiered badness** scoring, **bookmarks**, and **backtrace audit paths** for triage workflows. (source: wiki/sources/descriptions/0xdea__rhabdomancer.md)

Complements decompiled-pseudocode SAST via [[ida-security-scanner]] and string→pseudocode triage via [[augur]] (0xdea sibling). Sits in the same headless idalib automation lane as [[headless-ida]], [[ida-cli]], and [[ida-buddy]] when hunting risky native calls in game clients, anti-cheat drivers, and protected binaries.

## Links

- Repo: https://github.com/0xdea/rhabdomancer

## Related

[[overviews/reverse-engineering]] · [[augur]] · [[ida-security-scanner]] · [[headless-ida]] · [[ioctlpus]] · [[driver-vuln-analyzer-ida-plugin]] · [[list-of-ida-plugins]]
