---
title: augur
kind: entity
topics: [reverse-engineering, game-hacking]
sources:
  - wiki/sources/descriptions/0xdea__augur.md
updated: 2026-09-06
confidence: medium
---

# augur

**Headless IDA Pro analysis assistant** (0xdea; Rust + idalib). Extracts **strings** and related **Hex-Rays pseudocode** from binaries, organizing output into directories where each string maps to **decompiled functions that reference it** for scalable static triage. Targets Hex-Rays-supported binaries and is aimed at reverse engineers and vulnerability researchers building fast static analysis pipelines. (source: wiki/sources/descriptions/0xdea__augur.md)

Complements string-deobfuscation IDA plugins such as [[anti-xorstr]] and sits in the same **headless idalib automation** lane as [[rhabdomancer]], [[headless-ida]], and [[ida-cli]] when mapping string surfaces to decompiled logic in game clients, anti-cheat modules, and protected binaries.

## Links

- Repo: https://github.com/0xdea/augur

## Related

[[overviews/reverse-engineering]] · [[rhabdomancer]] · [[headless-ida]] · [[anti-xorstr]] · [[auto-re]] · [[hashdb-ida]] · [[list-of-ida-plugins]]
