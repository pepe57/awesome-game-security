---
title: cet-spoofing-detection
kind: entity
topics: [windows-kernel, anti-cheat]
sources:
  - wiki/sources/descriptions/0xjbb__cet-spoofing-detection.md
updated: 2026-09-05
confidence: medium
---

# cet-spoofing-detection

User-mode proof-of-concept that detects **stack spoofing in CET-enabled processes** by comparing the hardware **shadow stack** against the visible user-mode call stack. Missing or mismatched return-address frames between the two stacks expose spoofed call chains that pass conventional unwind walks. Built with Clang/CMake for Windows CET research in the `Detection:Spoof Stack` lane. (source: wiki/sources/descriptions/0xjbb__cet-spoofing-detection.md)

Complements defensive stack-walk implementations such as [[shadow-stack-walk]] and shadow-stack query PoCs such as [[query-shadow-stack]] when modeling hardware-backed return-address integrity checks against offensive [[stack-spoofing]] techniques.

## Links

- Repo: https://github.com/0xjbb/cet-spoofing-detection

## Related

[[stack-spoofing]] · [[shadow-stack-walk]] · [[query-shadow-stack]] · [[cet-research]] · [[cet-win10]] · [[overviews/anti-cheat]] · [[overviews/windows-kernel]]
