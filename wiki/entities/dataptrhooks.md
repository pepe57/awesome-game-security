---
title: DataptrHooks
kind: entity
topics: [windows-kernel, game-hacking, reverse-engineering]
sources:
  - wiki/sources/descriptions/0mWindyBug__DataptrHooks.md
updated: 2026-09-06
confidence: medium
---

# DataptrHooks

Windows kernel **proof of concept** for Ring0↔usermode communication through **`.data` pointer hooks** instead of standard IOCTL or named-device paths. Demonstrates syscall-reachable hook targets, including flows related to **`NtConvertBetweenAuxiliaryCounterAndPerformanceCounter`** and code-integrity querying. Ships user-mode clients plus kernel driver projects in C/C++, with research notes on locating indirect call sites through **control-flow-guard (CFG) artifacts**. Intended for kernel security researchers studying stealthier **mapped-driver communication** and detection tradeoffs. (source: wiki/sources/descriptions/0mWindyBug__DataptrHooks.md)

README lane: **`NtConvertBetweenAuxiliaryCounterAndPerformanceCounter`** — same auxiliary-counter syscall surface as [[poseidon]] and [[umap-mapper]], but focused on `.data` pointer redirection and CFG-assisted call-site discovery rather than full manual-map dispatch.

Mainly useful for game-security and reverse-engineering researchers mapping covert KM↔UM channels (adjacent to [[dataptrhookwin11]], [[dataptrswap-driver]], [[data-ptr-swap]], [[afd-irp-call-dispatch]], [[custom-data-ptr-swap-sample]], and [[data-communication]]).

## Links

- Repo: https://github.com/0mWindyBug/DataptrHooks

## Related

[[overviews/windows-kernel]] · [[overviews/game-hacking]] · [[poseidon]] · [[umap-mapper]] · [[dataptrhookwin11]] · [[dataptrswap-driver]] · [[data-ptr-swap]] · [[afd-irp-call-dispatch]] · [[custom-data-ptr-swap-sample]] · [[data-communication]]
