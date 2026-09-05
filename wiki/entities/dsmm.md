---
title: DSMM
kind: entity
topics: [windows-kernel, anti-cheat, game-hacking]
sources:
  - wiki/sources/descriptions/0xf1a__DSMM.md
updated: 2026-09-05
confidence: medium
---

# DSMM

Windows kernel **proof of concept** (0xf1a) that **manually maps** a custom driver image into a **discarded section** of a legitimate driver rather than allocating fresh kernel pool. The PoC demonstrates creating a **system thread after boot** while attempting to avoid immediate **PatchGuard-triggered** detection. Implementation is C-based driver development with supporting loader and structure code, aimed at advanced kernel stealth-loading experiments in authorized anti-cheat and security research environments. (source: wiki/sources/descriptions/0xf1a__DSMM.md)

README tags the project under **Discarded Driver Section Manual Map**. Complements signed-driver section-overlay mappers such as [[sinmapper]] and [[lpmapper]], host-section discovery via [[driver-dll-finder]], and post-map trace cleanup tools such as [[nullmap]]. Defensive analysts should pair section-size / image-bounds checks with NMI stack walks and [[kernel-pool-scanning]] when studying discarded-section manual-map evasion.

## Mechanism

- **Host reuse:** maps payload into unused/discarded space inside an already-loaded legitimate driver image.
- **Post-boot execution:** creates a system thread after boot instead of a conventional driver-load path.
- **PatchGuard awareness:** PoC explores avoiding immediate PatchGuard corruption triggers from stealth mapping.

## Links

- Repo: https://github.com/0xf1a/DSMM

## Related

[[sinmapper]] · [[lpmapper]] · [[driver-dll-finder]] · [[nullmap]] · [[iocreatedriver]] · [[patchguard]] · [[known-driver-mappers]] · [[kernel-pool-scanning]] · [[overviews/windows-kernel]] · [[overviews/anti-cheat]]
