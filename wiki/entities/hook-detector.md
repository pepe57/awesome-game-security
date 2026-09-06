---
title: Hook-Detector
kind: entity
topics: [anti-cheat, reverse-engineering, game-hacking]
sources:
  - wiki/sources/descriptions/0x6461726B__Hook-Detector.md
updated: 2026-09-06
confidence: medium
---

# Hook-Detector

Windows desktop application that scans loaded modules and processes to identify **inline** and **IAT** function/API hooks. Built in C++20 with a DirectX 11 and ImGui graphical interface; core logic combines a module scanner with PE parsing utilities to compare in-memory code against expected executable layouts. Uses remote PE parsing and manual PEB traversal. Targets x86 and x64 Windows builds for anti-cheat developers, game security researchers, and reverse engineers inspecting hook-based tampering in running software. (source: wiki/sources/descriptions/0x6461726B__Hook-Detector.md)

Complements process hook scanners such as [[hookhunter]], NTDLL hook detect/restore tooling such as [[nt-unhooker]], live-vs-disk integrity checks such as [[patch-finder]], and runtime PE scanners such as [[pe-sieve]] and [[xmalhunter]] in the `Detection:hook` lane.

## Links

- Repo: https://github.com/0x6461726B/Hook-Detector

## Related

[[hookhunter]] · [[hook-buster]] · [[nt-unhooker]] · [[patch-finder]] · [[pe-sieve]] · [[xmalhunter]] · [[overviews/anti-cheat]] · [[overviews/reverse-engineering]] · [[overviews/windows-kernel]]
