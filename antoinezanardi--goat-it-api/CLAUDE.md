# goat-it-api

> I work mostly on the repository `goat-it-api` (NestJS + Fastify, pnpm, Vitest, SWC). The repository has a root file named AGENTS.md with agent guidelines, quality gates, and workflows.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/goat-it-api/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Copilot Instructions

## Context

I work mostly on the repository `goat-it-api` (NestJS + Fastify, pnpm, Vitest, SWC). The repository has a root file named AGENTS.md with agent guidelines, quality gates, and workflows.

## Behavior

- When I ask for changes or guidance in `goat-it-api`, always read and follow `AGENTS.md`.
- If `AGENTS.md` is not in the current chat context, ask me to attach it and then comply with its rules (aliases, pnpm scripts, 100% coverage, Vitest, SWC).
- Prefer minimal edits, NestJS conventions, DTO validation, unit tests first, and ensure lint / typecheck / test:unit:cov and other mandatory commands pass.

---
> Source: [antoinezanardi/goat-it-api](https://github.com/antoinezanardi/goat-it-api) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-18 -->
