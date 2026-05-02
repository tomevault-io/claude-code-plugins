# ossinsight-cli

> This repository provides the `ossinsight` CLI and agent skill for querying OSSInsight's open source intelligence database (6B+ GitHub events).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ossinsight-cli/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md — OSSInsight CLI

This repository provides the `ossinsight` CLI and agent skill for querying OSSInsight's open source intelligence database (6B+ GitHub events).

## For AI Agents

Install the skill:
```bash
npx skills add kurom1ii/ossinsight-cli
```

Or install the CLI globally:
```bash
npm install -g github:kurom1ii/ossinsight-cli
```

## Available Commands

- `ossinsight trending [-l language] [-p period]` — Trending repos
- `ossinsight repo <owner/repo>` — Full repo analysis
- `ossinsight compare <repo1> <repo2>` — Compare two repos
- `ossinsight collections [-s keyword]` — Browse collections
- `ossinsight ranking <id> [-m metric] [-p period]` — Collection ranking
- `ossinsight stars <owner/repo> [-t type]` — Star demographics
- `ossinsight contributors <owner/repo> [-t type]` — Contributor analysis
- `ossinsight ask "<question>"` — AI-powered natural language query

## Compatibility

Works with: Claude Code, OpenClaw, Codex, Cursor, Gemini CLI, OpenCode, and any SKILL.md-compatible agent.

---
> Source: [kurom1ii/ossinsight-cli](https://github.com/kurom1ii/ossinsight-cli) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-28 -->
