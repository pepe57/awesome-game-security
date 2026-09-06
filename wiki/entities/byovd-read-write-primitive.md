---
title: BYOVD Read Write Primitive
kind: entity
topics: [windows-kernel, anti-cheat, game-hacking]
sources:
  - wiki/sources/descriptions/0xJs__BYOVD_read_write_primitive.md
updated: 2026-09-06
confidence: medium
---

# BYOVD Read Write Primitive

Educational BYOVD toolkit from 0xJs that exposes kernel read and write primitives on Windows through a vulnerable signed driver. Multiple C proof-of-concept tools resolve kernel offsets and symbols, then perform privileged memory operations via IOCTL-based communication. Capabilities include changing process protection levels, editing tokens, disabling ETW telemetry, removing kernel callbacks and minifilters, and modifying DSE state. Intended for authorized kernel security research and for studying anti-cheat or EDR hardening gaps—not a single-purpose kill driver, but a modular primitive-and-post-exploitation lab beside consoles such as [[kernel-cactus]] and [[edrsandblast]]. (source: wiki/sources/descriptions/0xJs__BYOVD_read_write_primitive.md)

## Links

- Repo: https://github.com/0xJs/BYOVD_read_write_primitive

## Related

[[byovd]] · [[kernel-cactus]] · [[edrsandblast]] · [[pplkiller]] · [[dse-pg-bypass]] · [[kernel-callbacks]] · [[etw-threat-intelligence]] · [[patchguard]] · [[overviews/windows-kernel]] · [[overviews/anti-cheat]]
