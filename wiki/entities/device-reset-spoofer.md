---
title: DeviceResetSpoofer
kind: entity
topics: [mobile-security, game-hacking, anti-cheat]
sources:
  - wiki/sources/descriptions/GJR787878__DeviceResetSpoofer.md
  - wiki/sources/README-categories.md
updated: 2026-09-06
confidence: medium
---

# DeviceResetSpoofer

**LSPosed module** that automatically assigns a **fresh device identity** to selected apps after their data is cleared. (source: wiki/sources/descriptions/GJR787878__DeviceResetSpoofer.md)

**Hooks:** Android ID, advertising ID (GAID), IMEI/MEID, Wi-Fi MAC, GSF ID, build fingerprint, and carrier metadata — each hook type toggled independently via Java Xposed hooks.

**Wipe detection:** A hidden sentinel file in the app's private directory detects data clears without relying on system broadcasts; users can also trigger manual identity resets from the module configuration UI.

Targets rooted devices running LSPosed on **Android 7–16**. README category: Cheat / Xposed.

Useful for studying post-ban recovery workflows, mobile device fingerprinting, anti-cheat HWID checks, and app-level hardware-ban evasion after clearing game data.

## Links

- Repo: https://github.com/GJR787878/DeviceResetSpoofer

## Related

[[overviews/mobile-security]] · [[overviews/game-hacking]] · [[overviews/anti-cheat]] · [[hidemyandroid]] · [[android-faker]] · [[nexus]] · [[copg]] · [[xposed-module-kit]] · [[mobile-anti-cheat]] · [[spoofing-collection]]
