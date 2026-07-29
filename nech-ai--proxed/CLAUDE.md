# general

> - Prefer complete, long-term implementations over workarounds or quick patches.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/general/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# General Rules

- Prefer complete, long-term implementations over workarounds or quick patches.
- Keep existing behavior, routes, and UI intact unless explicitly asked to remove/rename them.
- This repo is a Turborepo + Bun monorepo: use `bun` + root scripts; avoid introducing `npm`/`yarn` workflows.
- Prefer workspace imports (`@proxed/*`) and package entrypoints over deep relative imports across workspaces.
- Next.js apps default to React Server Components; add `"use client"` only when necessary.
- Security: never expose or log secrets (AI provider keys, Supabase keys, tokens). Provider calls should go through `apps/api` when applicable.

---
> Source: [nech-ai/proxed](https://github.com/nech-ai/proxed) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-29 -->
