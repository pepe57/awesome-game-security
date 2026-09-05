---
title: EyYoEtwWhereYouAt
kind: entity
topics: [windows-kernel, anti-cheat]
sources:
  - wiki/sources/descriptions/0xjbb__EyYoEtwWhereYouAt.md
updated: 2026-09-05
confidence: medium
---

# EyYoEtwWhereYouAt

ETW-based **process monitoring** PoC pairing a kernel driver (**EtwDriver**) with a user-mode analysis engine (**etw_exe**). The driver collects thread creation, image load, and memory allocation events; the user-mode component correlates those kernel notifications with expected ETW provider output to flag **missing ETW events**—a signal of ETW patching or blinded telemetry. The analysis engine also models suspicious behaviors such as injection and process hollowing. Built with CMake/MSVC and **krabs** for ETW consumption. (source: wiki/sources/descriptions/0xjbb__EyYoEtwWhereYouAt.md)

Sits on the defensive side of [[concepts/etw-threat-intelligence]] ETW-blind detection: complementary to registration tamper monitors such as [[etwti-fluctuation-monitor]] and Procmon-style ETW monitors such as [[openprocmon]], and useful when validating whether offensive ETW silencing such as [[amsi-etw-patch]] leaves observable gaps between kernel callbacks and user-mode ETW sessions.

## Links

- Repo: https://github.com/0xjbb/EyYoEtwWhereYouAt

## Related

[[concepts/etw-threat-intelligence]] · [[etwti-fluctuation-monitor]] · [[openprocmon]] · [[fibratus]] · [[amsi-etw-patch]] · [[cet-spoofing-detection]] · [[overviews/windows-kernel]] · [[overviews/anti-cheat]]
