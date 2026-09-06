---
title: armcall
kind: entity
topics: [anti-cheat, windows-kernel, reverse-engineering]
sources:
  - wiki/sources/descriptions/noahware__armcall.md
updated: 2026-09-06
confidence: medium
---

# armcall

**armcall** (noahware) is a header-only **C++20** library for making **direct Windows kernel syscalls on ARM64**. It parses **ntdll** exports, extracts the immediate operand from each **SVC** instruction, and dynamically generates executable stubs that invoke `svc` and return without routing through import thunks that anti-cheat or EDR software may hook. **AC_SYSCALL** macros provide a simple interface for invoking NT functions such as memory allocation and system time queries, with pluggable standard-library abstractions for custom environments. Useful for game security research, anti-cheat evasion studies, and low-level Windows reverse engineering on ARM64 (Windows on ARM). (source: wiki/sources/descriptions/noahware__armcall.md)

Complements x64-centric direct-syscall libraries such as [[inline-syscall]], [[syscalls-cpp]], and [[ebyte-syscalls]], ARM64 SSN reference tables such as [[syscall-tables]], and defensive origin checks such as [[syscall-detect]]. Same-author Windows kernel research includes [[apic]], [[darken-anticheat]], and [[hyper-rev]].

## Links

- Repo: https://github.com/noahware/armcall

## Related

[[inline-syscall]] · [[syscalls-cpp]] · [[ebyte-syscalls]] · [[doom-syscalls]] · [[syscall-tables]] · [[syscall-detect]] · [[ntsleuth]] · [[koidbg]] · [[apic]] · [[darken-anticheat]] · [[overviews/windows-kernel]] · [[overviews/anti-cheat]] · [[overviews/reverse-engineering]]
