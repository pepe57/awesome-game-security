---
title: ceserver-ios
kind: entity
topics: [mobile-security, game-hacking, reverse-engineering]
sources:
  - wiki/sources/descriptions/gmh5225__ceserver-ios.md
  - wiki/sources/descriptions/0xiuks__ceserver-ios.md
updated: 2026-09-05
confidence: medium
---

# ceserver-ios

**iOS port of Cheat Engine's ceserver** (0xiuks; C/C++) for memory inspection and manipulation on mobile apps. Runs on-device and exposes process memory through the **ceserver network protocol** so a desktop Cheat Engine client can connect remotely. Supports **jailed and jailbroken** workflows with memory search and editing, **breakpoints**, **watchpoints**, **pointer scanning**, and **instruction patching**. Includes iOS-facing components plus companion **Windows plugins** for iOS stack traces and RTTI. Primary use case is reverse engineering and game security research on iOS targets. (source: wiki/sources/descriptions/0xiuks__ceserver-ios.md)

Complements [[frida-ceserver]] when attach-based Frida is preferred or unavailable, on-device engines such as [[h5gg]], TrollStore debugger [[vansonmod]], and in-process patching via [[kittymemory-ios]].

## Links

- Repo: https://github.com/0xiuks/ceserver-ios

## Related

[[frida-ceserver]] · [[h5gg]] · [[vansonmod]] · [[kittymemory-ios]] · [[memory-server]] · [[wasm-ceserver]] · [[cheat-engine]] · [[overviews/mobile-security]] · [[overviews/game-hacking]] · [[overviews/reverse-engineering]]
