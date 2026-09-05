---
title: WinDbg Copilot
kind: entity
topics: [reverse-engineering, windows-kernel]
sources:
  - wiki/sources/descriptions/0xeb__windbg-copilot.md
  - wiki/sources/descriptions/DumpAnalysis__WinDbg_Copilot.md
updated: 2026-09-05
confidence: medium
---

# WinDbg Copilot

C++ WinDbg extension for **agentic debugging**: answers debugging questions, runs WinDbg commands automatically, and explains results. Supports multiple model providers, persistent conversation context, and decompilation-oriented assistance. Exposes HTTP and MCP-style interfaces plus a companion CLI for external tool integration. Aimed at crash triage, exploit debugging, and advanced Windows security analysis workflows. (source: wiki/sources/descriptions/0xeb__windbg-copilot.md)

Alternative Python implementation: [DumpAnalysis/WinDbg_Copilot](https://github.com/DumpAnalysis/WinDbg_Copilot) — ChatGPT-style in-session copilot that reads command output for guidance, explanations, and next-command suggestions via OpenAI/Azure OpenAI. (source: wiki/sources/descriptions/DumpAnalysis__WinDbg_Copilot.md)

Complements MCP-based WinDbg automation such as [[mcp-windbg]] and [[windbg-tool]], JS script collections such as [[windbg-scripts]] and [[windbg-cookbook]], and LLM decompiler extensions such as [[windbg-decompile-ext]] by offering in-debugger agentic assistance with optional external MCP/HTTP integration rather than static script libraries alone.

## Links

- Repo: https://github.com/0xeb/windbg-copilot (README tag: WinDbg Copilot - Agentic Debugging extension)
- Alternative: https://github.com/DumpAnalysis/WinDbg_Copilot

## Related

[[overviews/reverse-engineering]] · [[overviews/windows-kernel]] · [[mcp-windbg]] · [[windbg-tool]] · [[windbg-scripts]] · [[windbg-cookbook]] · [[windbg-decompile-ext]]
