---
title: DrvEye
kind: entity
topics: [windows-kernel, reverse-engineering]
sources:
  - wiki/sources/descriptions/0xDbgMan__DrvEye.md
updated: 2026-09-06
confidence: medium
---

# DrvEye

**DrvEye** (0xDbgMan) is a Windows kernel driver static analysis and bug-hunting tool for exploitation triage. It recovers IOCTL dispatch paths, performs taint analysis and emulation-based handler tracing, verifies certificates, runs YARA scans, and can generate PoCs to surface vulnerabilities in `.sys` binaries — including discovery of IOCTLs, symbolic links, and certificate checks. Primary users are kernel security researchers, BYOVD analysts, and reverse engineers assessing third-party or game-adjacent driver attack surface. (source: wiki/sources/descriptions/0xDbgMan__DrvEye.md)

Complements in-IDA triage via [[driver-vuln-analyzer-ida-plugin]] and export-based batch review via [[cognitor]] — focused on standalone static analysis with emulation, taint tracking, and PoC generation rather than interactive annotation or pipeline-scale AI review alone.

## Links

- Repo: https://github.com/0xDbgMan/DrvEye

## Related

[[overviews/windows-kernel]] · [[overviews/reverse-engineering]] · [[driver-vuln-analyzer-ida-plugin]] · [[deepzero]] · [[cognitor]] · [[driver-buddy-reloaded]] · [[ioctl-helper]] · [[cfb]] · [[byovd]]
