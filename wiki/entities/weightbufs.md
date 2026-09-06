---
title: weightBufs
kind: entity
topics: [mobile-security, reverse-engineering]
sources:
  - wiki/sources/descriptions/0x36__weightBufs.md
updated: 2026-09-06
confidence: medium
---

# weightBufs

Multi-stage XNU kernel read/write exploit chain targeting Apple devices with **Apple Neural Engine (ANE)** support. Combines several vulnerabilities in ANE-related components and documents practical constraints, tested device ranges, and exploitation reliability notes. The repository mixes Objective-C, C, and iOS app scaffolding with low-level **IOKit** and **IOSurface** interaction helpers. Targets **iOS 15** and **macOS 12**; aimed at iOS and macOS security researchers studying multi-stage kernel exploitation on Neural-Engine-capable hardware. (source: wiki/sources/descriptions/0x36__weightBufs.md)

Complements IOSurface-centric kernel R/W study via [[xnu-1day-practice]] and [[momentarius]], and file-descriptor exploit frameworks such as [[kfd]] — this chain focuses on ANE-component bugs rather than Mach voucher/IOSurface-only or kfd-style FD primitives alone. Same author (0x36) publishes Android/Mali GPU kernel exploitation via [[pixel-gpu-exploit]].

## Links

- Repo: https://github.com/0x36/weightBufs

## Related

[[overviews/mobile-security]] · [[overviews/reverse-engineering]] · [[xnu-1day-practice]] · [[momentarius]] · [[kfd]] · [[kfd-explorer]] · [[pixel-gpu-exploit]] · [[dopamine]] · [[xnu-qemu-arm64]]
