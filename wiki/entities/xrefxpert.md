---
title: XrefXpert
kind: entity
topics: [reverse-engineering, game-hacking]
sources:
  - wiki/sources/descriptions/0xGotcha__XrefXpert.md
updated: 2026-09-06
confidence: medium
---

# XrefXpert

IDA Pro plugin (Python, IDA APIs, PyQt) that improves **cross-reference navigation** through a dockable viewer panel. Lists function xrefs in real time, supports click-to-jump navigation, and provides hotkeys for fast movement between references. Adds filters for immediates, parameter counts, and binary signatures. Intended for reverse engineering tasks such as game binary analysis and vulnerability research. (source: wiki/sources/descriptions/0xGotcha__XrefXpert.md)

Complements xref **creation/recovery** tools [[find-xrefs]] and [[xrefgen]] and xref **extension** workflows via [[xrefsext]] when triaging large game clients and anti-cheat modules in IDA. Cheat / IDA Plugins lane.

## Capabilities

- **Dockable xref viewer** — live function xref list beside the disassembly/decompiler view.
- **Click-to-jump + hotkeys** — fast traversal between reference sites.
- **Filtering** — narrow xrefs by immediates, parameter counts, and binary signatures.

## Links

- Repo: https://github.com/0xGotcha/XrefXpert

## Related

[[overviews/reverse-engineering]] · [[overviews/game-hacking]] · [[find-xrefs]] · [[xrefgen]] · [[xrefsext]] · [[findfunc]] · [[ida-plugins]] · [[list-of-ida-plugins]]
