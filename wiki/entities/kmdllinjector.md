---
title: KMDllInjector
kind: entity
topics: [windows-kernel, game-hacking, anti-cheat]
sources:
  - wiki/sources/descriptions/0xPrimo__KMDllInjector.md
updated: 2026-09-06
confidence: medium
---

# KMDllInjector

Windows **kernel-mode DLL injection framework** (C++) that targets processes during **early startup**. Supports callback-based triggering via **process-creation** or **image-load** notifications, demonstrates hooking **ntdll** loader routines with **position-independent shellcode**, and includes a **kernel APC** injection path for early user-mode execution timing. Used for advanced process-injection research in controlled security testing. (source: wiki/sources/descriptions/0xPrimo__KMDllInjector.md)

README lane: kernel-mode DLL Injector.

## Links

- Repo: https://github.com/0xPrimo/KMDllInjector

## Related

[[kernel-dll-injector]] · [[kernelmode-dll-injector]] · [[injdrv]] · [[kinject]] · [[stealthy-kernelmode-injector]] · [[kernel-callbacks]] · [[apc-research]] · [[windows-process-injection]] · [[overviews/windows-kernel]] · [[overviews/game-hacking]] · [[overviews/anti-cheat]]
