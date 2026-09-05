---
title: debugoff
kind: entity
topics: [anti-cheat, reverse-engineering]
sources:
  - wiki/sources/descriptions/0xor0ne__debugoff.md
updated: 2026-09-05
confidence: medium
---

# debugoff

Linux **Rust anti-analysis and anti-debugging library** from 0xor0ne for security research on hardening binaries against reverse engineering. Uses **direct syscalls without libc dependencies** and adds **syscall-level obfuscation** to complicate static analysis. Runs **chained and randomized ptrace-based checks** that validate expected behavior and **terminate execution** when tampering is detected. (source: wiki/sources/descriptions/0xor0ne__debugoff.md)

Complements Linux detection tooling such as [[ladd]] and [[adbg]], Windows integratable libraries such as [[cpp-anti-debug]] and [[antidbg]], and educational packers such as [[kiteshield]] that also use ptrace-based anti-debug on Linux.

## Links

- Repo: https://github.com/0xor0ne/debugoff

## Related

[[overviews/anti-cheat]] · [[overviews/reverse-engineering]] · [[ladd]] · [[adbg]] · [[cpp-anti-debug]] · [[antidbg]] · [[kiteshield]] · [[pince]]
