---
title: BYOVD EDRKiller
kind: entity
topics: [windows-kernel, anti-cheat, game-hacking]
sources:
  - wiki/sources/descriptions/0xJs__BYOVD_EDRKiller.md
updated: 2026-09-06
confidence: medium
---

# BYOVD EDRKiller

Educational Windows BYOVD proof of concept from 0xJs that abuses a vulnerable signed driver (**`BdApiUtil64.sys`**) to terminate selected security processes. The project documents reverse engineering of the driver interface—device naming, IOCTL selection, and required input buffer structure. The C implementation automates driver deployment, target process enumeration, repeated termination attempts, and cleanup on exit. Intended for authorized red-team research on defensive product resilience and kernel attack surface, beside the BdApiUtil branch in [[entities/byovd|BYOVD Lab]] and sibling 0xJs toolkit [[byovd-read-write-primitive]]. (source: wiki/sources/descriptions/0xJs__BYOVD_EDRKiller.md)

## Links

- Repo: https://github.com/0xJs/BYOVD_EDRKiller
- Driver path: https://github.com/0xJs/BYOVD_EDRKiller/tree/main/BdApiUtil (`BdApiUtil64.sys`)

## Related

[[byovd]] · [[byovd-read-write-primitive]] · [[av-edr-killer]] · [[terminator]] · [[process-killer-byovd]] · [[edrsandblast]] · [[overviews/windows-kernel]] · [[overviews/anti-cheat]]
