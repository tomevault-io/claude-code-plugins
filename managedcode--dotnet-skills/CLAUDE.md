# dotnet-skills

> Use `AGENTS.md` as the repository-wide source of truth for workflow, catalog structure, release policy, and skill maintenance rules.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/dotnet-skills/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GitHub Copilot Instructions

Use `AGENTS.md` as the repository-wide source of truth for workflow, catalog structure, release policy, and skill maintenance rules.

This repository's human-maintained catalog source lives under `catalog/<type>/<package>/` with package `manifest.json`, nested `skills/*/SKILL.md`, and nested `agents/*/AGENT.md`. When project-local Copilot skills are installed, they should be placed in `.github/skills/`.

---
> Source: [managedcode/dotnet-skills](https://github.com/managedcode/dotnet-skills) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-19 -->
