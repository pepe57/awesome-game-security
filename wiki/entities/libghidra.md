---
title: libghidra
kind: entity
topics: [reverse-engineering, game-hacking]
sources:
  - wiki/sources/descriptions/0xeb__libghidra.md
updated: 2026-09-05
confidence: medium
---

# libghidra

**libghidra** — C++/Rust/Python library wrapping Ghidra's native decompiler stack (**SLEIGH** + **Pcode**) for headless binary analysis without a JVM. Exposes typed APIs for disassembly, decompilation, control-flow graph construction, type-system manipulation, and cross-reference queries against Ghidra program databases. Supports a **LibGhidraHost** HTTP Ghidra extension backend or an offline **Sleigh** backend for automation pipelines. (source: wiki/sources/descriptions/0xeb__libghidra.md)

Complements JVM-based Ghidra automation paths such as [[ghidra-bridge]] (CPython ↔ in-process Jython) and agent MCP servers like [[ghidra-headless-mcp]]; sits beside headless IDA tooling ([[headless-ida]], [[ida-cli]]) when building native-language RE pipelines that need Ghidra-quality decompilation outside the desktop UI.

## Links

- Repo: https://github.com/0xeb/libghidra

## Related

[[ghidra]] · [[ghidra-bridge]] · [[ghidra-headless-mcp]] · [[headless-ida]] · [[gdbghidra]] · [[overviews/reverse-engineering]] · [[overviews/game-hacking]]
