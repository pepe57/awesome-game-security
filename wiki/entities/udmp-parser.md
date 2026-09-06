---
title: udmp-parser
kind: entity
topics: [reverse-engineering, windows-kernel]
sources:
  - wiki/sources/descriptions/0vercl0k__udmp-parser.md
updated: 2026-09-06
confidence: medium
---

# udmp-parser

**udmp-parser** (0vercl0k) is a **cross-platform C++ parser** for Windows **user-mode minidump** (`.dmp`) files. It exposes thread data, register contexts, virtual memory ranges, and loaded modules through library APIs and a standalone parser utility. The repository ships CMake build files, tests, and optional **Python bindings** for automation—aimed at debugger tooling, reverse engineering, and incident-response dump triage. (source: wiki/sources/descriptions/0vercl0k__udmp-parser.md)

Complements sibling 0vercl0k kernel crash-dump parsing via [[kdmp-parser]], Python minidump libraries such as [[minidump]] / [[minidumpreader]], C/C++ format libraries such as [[libmdmp]], Ghidra-native dump loading via [[ghidra-minidump-loader]], Unicorn-based offline execution via [[dumpulator]], sibling 0vercl0k execution-trace symbolization via [[symbolizer]], and sibling 0vercl0k fuzzing tooling [[wtf]].

## Links

- Repo: https://github.com/0vercl0k/udmp-parser

## Related

[[kdmp-parser]] · [[minidump]] · [[minidumpreader]] · [[libmdmp]] · [[ghidra-minidump-loader]] · [[dumpulator]] · [[symbolizer]] · [[wtf]] · [[overviews/reverse-engineering]] · [[overviews/windows-kernel]]
