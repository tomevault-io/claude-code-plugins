# matilha-builders

> For UI-related tasks, always use existing shadcn-svelte primitives (`apps/web/src/lib/components/ui/`) instead of building a component from scratch. If the needed primitive isn't installed yet, add it with:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/matilha-builders/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Instructions

## UI components (apps/web)

For UI-related tasks, always use existing shadcn-svelte primitives (`apps/web/src/lib/components/ui/`) instead of building a component from scratch. If the needed primitive isn't installed yet, add it with:

```bash
pnpm exec shadcn-svelte add <component>
```

(run from `apps/web`). Only hand-roll a component when no shadcn-svelte primitive fits.

---
> Source: [nagringa-dev/matilha-builders](https://github.com/nagringa-dev/matilha-builders) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-16 -->
