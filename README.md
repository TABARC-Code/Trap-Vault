# Trap Vault
> A markdown-first, Obsidian-native knowledge system for Claude Code, co-worker workflows, and optional local MCP tooling.

<p align="center">
  <img alt="Status" src="https://img.shields.io/badge/status-variant--new%20%2B%20mcp-3b82f6?style=for-the-badge">
  <img alt="Markdown First" src="https://img.shields.io/badge/markdown-first-111827?style=for-the-badge">
  <img alt="Obsidian" src="https://img.shields.io/badge/obsidian-native-7c3aed?style=for-the-badge">
  <img alt="Claude Code" src="https://img.shields.io/badge/claude%20code-ready-f59e0b?style=for-the-badge">
  <img alt="MCP" src="https://img.shields.io/badge/mcp-optional-10b981?style=for-the-badge">
  <img alt="Cron" src="https://img.shields.io/badge/cron-optional-0ea5e9?style=for-the-badge">
  <img alt="Git" src="https://img.shields.io/badge/git-backed-ef4444?style=for-the-badge">
</p>

---

## What this is

Trap Vault is a markdown-first, Obsidian-native knowledge system designed to stay structured over time instead of decaying into note sprawl.

It combines:
- Dewey-style classification
- Claude co-worker workflows
- Persistent wiki-style synthesis
- Optional MCP tool layer

---

## Quick start

```bash
git clone https://github.com/TABARC-Code/Trap-Vault.git
```

Open in Obsidian and Claude Code simultaneously.

---

## Structure

```mermaid
flowchart LR
    A[Raw sources] --> B[Claude]
    B --> C[Concepts]
    B --> D[Datasets]
    B --> E[Synthesis]
    C --> F[Field hubs]
    D --> F
    E --> F
```

---

## Core principle

> You think. Claude maintains.

---

## MCP

Optional local tool layer included in `mcp_server/`.

---

## Status

Active development
