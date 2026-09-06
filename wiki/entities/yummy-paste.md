---
title: yummyPaste
kind: entity
topics: [reverse-engineering, game-hacking]
sources:
  - wiki/sources/descriptions/0ffffffffh__yummyPaste.md
updated: 2026-09-06
confidence: medium
---

# yummyPaste

[[x64dbg]] plugin that pastes **binary byte data from text** directly into memory views. Built in C++ on the x64dbg plugin SDK and supports multiple input formats: C-style byte arrays, escaped shellcode strings, comma-separated decimals, and space-separated decimal sequences. Targets disassembler and dump-window workflows for reverse engineers and exploit developers who need quick patching and byte injection during live analysis. (source: wiki/sources/descriptions/0ffffffffh__yummyPaste.md)

Complements assembler/patch tooling such as [[multiline-ultimate-assembler]] and scripted memory workflows via [[x64dbgpython]] when the task is pasting preformatted byte blocks rather than assembling instructions or running automation scripts. README category: paste string formatted byte data block into x64dbg easy.

## Links

- Repo: https://github.com/0ffffffffh/yummyPaste

## Related

[[overviews/reverse-engineering]] · [[overviews/game-hacking]] · [[x64dbg]] · [[multiline-ultimate-assembler]] · [[x64dbgpython]] · [[x64dbg-script]]
