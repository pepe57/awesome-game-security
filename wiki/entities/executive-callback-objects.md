---
title: ExecutiveCallbackObjects
kind: entity
topics: [windows-kernel, anti-cheat]
sources:
  - wiki/sources/descriptions/0xcpu__ExecutiveCallbackObjects.md
updated: 2026-09-06
confidence: medium
---

# ExecutiveCallbackObjects

Research collection on Windows **executive callback objects** and their runtime behavior. Combines technical notes with C-based kernel proof-of-concept samples that register, inspect, and analyze callback activity. Coverage spans multiple callback families across networking, system state, boot flow, and security-related components. Primary audience is Windows internals researchers, telemetry visibility studies, and anti-cheat or EDR-oriented analysis. (source: wiki/sources/descriptions/0xcpu__ExecutiveCallbackObjects.md)

Complements notify/object callback catalogs such as [[kernel-callback-functions-list]] and enumeration tooling such as [[openark]] by focusing on executive callback registration mechanics and live inspection PoCs. Pairs with syscall-intercept research from the same author such as [[win-alt-syscall-handler]] and operational **PsAltSystemCallHandlers** monitors such as [[callmon]] when mapping kernel callback surfaces relevant to AC telemetry.

## Links

- Repo: https://github.com/0xcpu/ExecutiveCallbackObjects (README tag: Callback)

## Related

[[overviews/windows-kernel]] · [[overviews/anti-cheat]] · [[kernel-callbacks]] · [[kernel-callback-functions-list]] · [[win-alt-syscall-handler]] · [[callmon]] · [[openark]] · [[bustercall]]
