---
title: Game Debug Menu
kind: entity
topics: [game-engine, game-hacking]
sources:
  - wiki/sources/descriptions/000-aki-000__GameDebugMenu.md
updated: 2026-09-07
confidence: medium
---

# Game Debug Menu

Unreal Engine debug menu plugin combining a C++ module with Blueprint/UI assets to provide in-game debugging interfaces. Key capabilities include executing console commands, editing gameplay properties and functions at runtime, localization support, and persisting menu state data. Aimed at game developers and QA teams who need runtime testing and tuning tools—not an external memory cheat or anti-cheat bypass. (source: wiki/sources/descriptions/000-aki-000__GameDebugMenu.md)

Sits in the legitimate Unreal debug/cheat-command lane beside `UCheatManager` reflection menus such as [[cheat-manager-menu]] and ImGui tooling such as [[unreal-imgui-tools]]. Dev-only debug surfaces like console command execution and live property editing are relevant when studying what runtime tuning hooks may remain reachable in non-Shipping builds.

## Links

- Repo: https://github.com/000-aki-000/GameDebugMenu (README: Debug Menu for UnrealEngine4)

## Related

[[overviews/game-engine]] · [[overviews/game-hacking]] · [[cheat-manager-menu]] · [[unreal-imgui-tools]] · [[unrealcpp]] · [[unreal-mod-loader]]
