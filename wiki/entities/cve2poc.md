---
title: CVE2PoC
kind: entity
topics: [reverse-engineering, game-hacking]
sources:
  - wiki/sources/descriptions/0liverFlow__CVE2PoC.md
updated: 2026-09-06
confidence: medium
---

# CVE2PoC

Python tool that **aggregates public PoCs and exploits** for a given CVE ID from **GitHub**, **ExploitDB**, **Nuclei**, and **Metasploit**. Enriches hits with **CVSS**, **EPSS**, and **CISA KEV** context, and can emit **Docker labs**, bug-bounty write-ups, **CVE↔CPE** mapping, plus **JSON or HTML** reports. Primarily useful for game-security researchers and reverse engineers studying offensive techniques in the cheat / RE-tools lane. (source: wiki/sources/descriptions/0liverFlow__CVE2PoC.md)

README lane: per-CVE PoC aggregation with multi-source exploit discovery and severity/context enrichment — complements keyword/product search CLIs such as [[cve-maker]].

## Links

- Repo: https://github.com/0liverFlow/CVE2PoC

## Related

[[overviews/reverse-engineering]] · [[overviews/game-hacking]] · [[cve-maker]] · [[pocsmith]] · [[localroot-all-cve]] · [[retools]] · [[android-kernel-cve-pocs]]
