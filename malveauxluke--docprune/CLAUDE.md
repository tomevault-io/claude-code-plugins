# docprune

> This repository concerns token compression for document QA.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/docprune/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## Scope

This repository concerns token compression for document QA.

## Context routing

Read `agent-context/INDEX.md` first. Treat inherited specifications, research,
and SOL material as nonbinding reference unless `agent-context/CURRENT_TASK.md`
explicitly activates work.

## Working rules

- Preserve immutable sources and keep generated or large artifacts outside Git.
- Make small, reviewable changes and surface material assumptions.
- Do not start an experiment, model run, or SOL job without a current task and
  explicit handoff.
- Keep navigation files current when adding durable research material.
- Never add secrets, model weights, datasets, caches, or generated outputs.

---
> Source: [MalveauxLuke/DocPrune](https://github.com/MalveauxLuke/DocPrune) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-24 -->
