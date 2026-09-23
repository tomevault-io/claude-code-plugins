# ai-saas-starter

> Read AGENTS.md at the repo root — it is the full operating manual and wins over these lines.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ai-saas-starter/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

Read AGENTS.md at the repo root — it is the full operating manual and wins over these lines.
Use pnpm only; done means `pnpm typecheck && pnpm lint && pnpm test` pass.
Never: edit applied migrations, mutate `credit_transactions`, touch credit tables outside `src/lib/credits/`, or weaken Stripe webhook signature checks.
Ask before adding dependencies, changing DB schema, or changing plans/prices.
UI changes follow DESIGN.md ("The Ledger"): 2px radius, no gradients/shadows, ledger rows over card grids, no emoji.

---
> Source: [nikandr-surkov/ai-saas-starter](https://github.com/nikandr-surkov/ai-saas-starter) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-23 -->
