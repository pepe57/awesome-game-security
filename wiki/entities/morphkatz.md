---
title: MorphKatz
kind: entity
topics: [anti-cheat, reverse-engineering]
sources:
  - wiki/sources/descriptions/0xMohammedHassan__morphkatz.md
updated: 2026-09-06
confidence: medium
---

# MorphKatz

Polymorphic mutation engine for mimikatz on Windows x64. Disassembles the input PE, performs CFG analysis, and applies instruction-level morphing—register renaming, junk insertion, equivalent substitution—plus data-flow obfuscation to emit semantically identical but byte-different binary variants that evade signature-based detection. README positions it as a polymorphic PE rewriter for Windows x64 in the Anti Cheat → Obfuscation Engine lane. (source: wiki/sources/descriptions/0xMohammedHassan__morphkatz.md)

Useful alongside opcode-equivalent mutators such as [[beatrice-py]], polymorphic shredders such as [[shredder-rs]], and PE obfuscators such as [[alcatraz]] for studying AV/AC signature-mutation defenses—not a game client or AC product itself.

## Links

- Repo: https://github.com/0xMohammedHassan/morphkatz

## Related

[[overviews/anti-cheat]] · [[overviews/reverse-engineering]] · [[beatrice-py]] · [[shredder-rs]] · [[r2morph]] · [[alcatraz]]
