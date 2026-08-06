# manifest

> Manifest terminology is directional:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/manifest/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Manifest Agent Guidelines

## Domain Terminology

Manifest terminology is directional:

- A **Manifest Request** is one logical request from an agent to Manifest and lives in `requests`.
- A **Provider Attempt** is one request from Manifest to an AI provider and lives in `agent_messages`.

[`docs/glossary.md`](docs/glossary.md) is the canonical contract for statuses, ordering, recovery, database mapping, and counting rules. Do not duplicate those definitions in agent guides.

---
> Source: [mnfst/manifest](https://github.com/mnfst/manifest) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-26 -->
