# core

> Core repo rules — always apply

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/core/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Full manual: AGENTS.md at the repo root. The essentials:

- pnpm only. Never npm or yarn.
- Done = `pnpm typecheck && pnpm lint && pnpm test` pass; new features
  include tests.
- Server Actions for mutations; API routes only for webhooks and the Better
  Auth handler. Server Components by default; `"use client"` only for
  interactivity.
- Zod at every external boundary (forms, webhooks, env). Env is read only
  through `src/lib/env.ts`.
- Re-check the session server-side in every action and `(app)` page — never
  trust middleware alone.
- Money in integer cents; credits in integers.
- NEVER: edit applied migrations in `drizzle/`; mutate/delete
  `credit_transactions` rows; touch credit tables outside `src/lib/credits/`;
  weaken Stripe webhook signature checks; log secrets; commit `.env`.
- ASK FIRST: new dependencies, schema changes, plan/price changes.
- UI follows DESIGN.md: 2px radius, no gradients/shadows/blur, ledger rows
  not card grids, accent green scarce, no emoji.

---
> Source: [nikandr-surkov/ai-saas-starter](https://github.com/nikandr-surkov/ai-saas-starter) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-23 -->
