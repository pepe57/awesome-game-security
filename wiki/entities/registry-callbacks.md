---
title: registry-callbacks
kind: entity
topics: [windows-kernel, game-hacking, anti-cheat]
sources:
  - wiki/sources/descriptions/0xGREG__registry-callbacks.md
updated: 2026-09-06
confidence: medium
---

# registry-callbacks

**registry-callbacks** (0xGREG) is a Windows **kernel and user-mode proof of concept** that communicates through **registry callbacks**. It demonstrates registering a callback through a **jump gadget in a legitimate module** so a **manually mapped driver** can receive commands without a conventional IOCTL device surface. The C and C++ code implements operations such as **virtual memory read and write**, **protected memory patching**, **process base lookup**, and **heartbeat checks**. Intended as a reference for **kernel communication** and **anti-cheat evasion research** in controlled environments; README tag `[Registry Callback]`. (source: wiki/sources/descriptions/0xGREG__registry-callbacks.md)

Sits in the same **registry-callback** and covert **KM↔UM IPC** lane as [[common-registry-jmp-rcx]], [[common-registry]], [[boundcallback]], [[evcommunication]], and [[km-um-communication]].

## Links

- Repo: https://github.com/0xGREG/registry-callbacks

## Related

[[kernel-callbacks]] · [[common-registry-jmp-rcx]] · [[common-registry]] · [[boundcallback]] · [[evcommunication]] · [[km-um-communication]] · [[overviews/windows-kernel]] · [[overviews/game-hacking]]
