---
title: snapshot
kind: entity
topics: [reverse-engineering, windows-kernel]
sources:
  - wiki/sources/descriptions/0vercl0k__snapshot.md
updated: 2026-09-06
confidence: medium
---

# snapshot

**snapshot** (0vercl0k) is a **Rust WinDbg extension** that captures a complete snapshot of a running virtual machine for offline analysis and snapshot-based fuzzing. It serializes CPU state—general-purpose registers, segment descriptors, MSRs, FPU stack entries, and SSE registers—into JSON and writes a physical memory crash dump alongside it. The extension supports full-kernel and active-kernel dump modes, is built with the Windows DbgEng API via the **dbgeng** crate as a cdylib loaded into live x64 kernel debugging sessions, and serves as a reference for implementing WinDbg extensions in Rust. Primary use is snapshot-based fuzzing workflows with companion tooling such as [[wtf]]; security researchers freeze VM execution state for kernel and user-mode vulnerability research on Windows targets. (source: wiki/sources/descriptions/0vercl0k__snapshot.md)

## Links

- Repo: https://github.com/0vercl0k/snapshot

## Related

[[wtf]] · [[symbolizer]] · [[udmp-parser]] · [[windbg-tool]] · [[windbg-js-scripts]] · [[overviews/reverse-engineering]] · [[overviews/windows-kernel]]
