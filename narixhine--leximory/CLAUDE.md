# leximory

> <!-- BEGIN:nextjs-agent-rules -->

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/leximory/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

<!-- BEGIN:nextjs-agent-rules -->
 
# Next.js: ALWAYS read docs before coding
 
Before any Next.js work, find and read the relevant doc in `node_modules/next/dist/docs/`. Your training data is outdated — the docs are the source of truth.
 
<!-- END:nextjs-agent-rules -->

<!-- BEGIN:type-check-agent-rules -->
 
# Type Check: ALWAYS use turbo or pnpm to type-check

If you need to type-check, use `pnpm run check-types` (in an app directory) or `turbo check-types` (for the entire Turborepo) instead of `npm` or `tsc`.
 
<!-- END:type-check-agent-rules -->

---
> Source: [NarixHine/leximory](https://github.com/NarixHine/leximory) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-05 -->
