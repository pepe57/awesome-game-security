---
title: Sanctum
kind: entity
topics: [anti-cheat, windows-kernel]
sources:
  - wiki/sources/descriptions/0xflux__Sanctum.md
updated: 2026-09-05
confidence: medium
---

# Sanctum

Experimental **Windows endpoint detection and response (EDR)** proof-of-concept built primarily in **Rust**. The stack combines a **kernel driver**, a **user-mode engine**, and a **Tauri** operator interface to monitor process, thread, file-system, and system-call activity. Components include **ETW consumers**, a **file-system minifilter**, and kernel-side hooking and containment logic for telemetry and response. Primary use case is low-level security research and prototyping defensive tooling on modern Windows systems—aimed at detecting modern malware techniques beyond conventional antivirus. (source: wiki/sources/descriptions/0xflux__Sanctum.md)

README category: `[EDR]`.

## Capabilities

| Area | Role |
|------|------|
| **Kernel driver** | Minifilter, kernel-side hooking, containment logic |
| **User-mode engine** | Process/thread/file/syscall monitoring and response orchestration |
| **Telemetry** | ETW consumers for event ingestion |
| **Operator UI** | Tauri-based management interface |

## Positioning

Rust-built experimental EDR on the defensive side—complements full-stack open-source references such as [[openedr]], [[bluespawn]], and [[whids]], educational AC stacks such as [[peregrine-anticheat]] that also pair kernel minifilters with Tauri, and ETW observability tools such as [[fibratus]] and [[openprocmon]] when studying how endpoint agents combine kernel telemetry, ETW, and response workflows.

## Links

- Repo: https://github.com/0xflux/Sanctum

## Related

[[overviews/anti-cheat]] · [[overviews/windows-kernel]] · [[openedr]] · [[bluespawn]] · [[whids]] · [[peregrine-anticheat]] · [[fibratus]] · [[openprocmon]] · [[concepts/etw-threat-intelligence]] · [[concepts/kernel-callbacks]] · [[stresser]]
