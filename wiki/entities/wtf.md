---
title: WTF
kind: entity
topics: [reverse-engineering, game-hacking, windows-kernel]
sources:
  - wiki/sources/descriptions/0vercl0k__wtf.md
updated: 2026-09-06
confidence: medium
---

# WTF

**WTF** (0vercl0k) is a **distributed snapshot-based fuzzer** for Windows with experimental Linux support. It combines **coverage-guided fuzzing** with multiple execution backends—emulator-driven and **virtualization-driven snapshot execution** for both user-mode and kernel-mode targets. The C++ codebase ships auxiliary scripts and tooling for corpus handling, coverage processing, and trace-oriented workflows, aimed at vulnerability researchers fuzzing complex software such as game components, drivers, and system services. (source: wiki/sources/descriptions/0vercl0k__wtf.md)

Companion WinDbg snapshot capture via [[snapshot]] (Rust extension; JSON CPU state + physical memory crash dump from live x64 kernel debug sessions) feeds VM-state inputs into that fuzzing workflow.

Sits beside in-process Windows AFL ([[winafl]]), Intel-PT hypervisor fuzzing ([[qemu-nyx]]), fuzz-target discovery ([[fuzzable]]), and VT-assisted debug/trace stacks ([[hyperdbg]], [[rax]]) in the snapshot-reset / coverage-guided fuzzing lane.

## Links

- Repo: https://github.com/0vercl0k/wtf

## Related

[[snapshot]] · [[winafl]] · [[qemu-nyx]] · [[fuzzable]] · [[hyperdbg]] · [[rax]] · [[dynamic-binary-instrumentation]] · [[overviews/reverse-engineering]] · [[overviews/game-hacking]] · [[overviews/windows-kernel]]
