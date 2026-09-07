---
title: PetalAntiFreecam
kind: entity
topics: [anti-cheat, game-hacking]
sources:
  - wiki/sources/descriptions/boggymc__PetalAntiFreecam.md
updated: 2026-09-07
confidence: medium
---

# PetalAntiFreecam

Minecraft server plugin that mitigates freecam cheating by stripping terrain below a configurable Y level from chunk packets sent to players who are above that cutoff. Written in Java for Paper and CanvasMC 1.21, it hooks outgoing chunk data with PacketEvents and uses a ChunkMasker to replace hidden sections with air while filtering tile entities, then refreshes chunks as players move with a per-tick budget to limit network load. Administrators can tune restore and hide Y thresholds, reload settings at runtime, and rely on optional CanvasMC visibility listeners for async teleport handling. Targets multiplayer server operators who need lightweight, server-side anti-cheat against client-side camera exploits rather than kernel-level or commercial anti-cheat suites. (source: wiki/sources/descriptions/boggymc__PetalAntiFreecam.md)

## Mitigation stack

PacketEvents outgoing chunk interception; ChunkMasker replaces underground sections with air below configurable hide-Y for players above cutoff; tile-entity filtering; per-tick refresh budget; runtime reload; optional CanvasMC async teleport visibility listeners.

## Links

- Repo: https://github.com/boggymc/PetalAntiFreecam

## Related

[[overviews/anti-cheat]] · [[overviews/game-hacking]] · [[antixrayviewer]] · [[bs-anticheat]] · [[larping-anti-cheat]] · [[anticheat-qa]] · [[minecraft-anticheat-list]]
