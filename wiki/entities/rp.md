---
title: rp
kind: entity
topics: [reverse-engineering, game-hacking]
sources:
  - wiki/sources/descriptions/0vercl0k__rp.md
updated: 2026-09-06
confidence: medium
---

# rp

**rp** (rp++; 0vercl0k) is a **fast C++ ROP gadget finder** for return-oriented programming analysis. It scans **PE**, **ELF**, and **Mach-O** binaries across **x86**, **x64**, **ARM**, and **ARM64**, searching both instruction gadgets and useful pointer values. The cross-platform implementation integrates disassembly-related dependencies and targets exploit developers and reverse engineers building ROP chains and auditing binary attack surfaces. (source: wiki/sources/descriptions/0vercl0k__rp.md)

Complements Python gadget scanner [[ropgadget]], Rust [[ropgadget-rs]], semantic chain builder [[ropium]], and sibling 0vercl0k tooling such as [[wtf]], [[symbolizer]], and [[udmp-parser]].

## Links

- Repo: https://github.com/0vercl0k/rp

## Related

[[ropgadget]] · [[ropgadget-rs]] · [[ropium]] · [[exrop]] · [[angrop]] · [[agafi]] · [[rop-compiler]] · [[wtf]] · [[symbolizer]] · [[udmp-parser]] · [[overviews/reverse-engineering]] · [[overviews/game-hacking]]
