# tanstack-hono

> This file is intentionally short. Use `AGENTS.md` as the source of truth.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tanstack-hono/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Cursor Rules

This file is intentionally short. Use `AGENTS.md` as the source of truth.

## Non-Negotiables

- Package manager: `npm`
- Do not edit `src/routeTree.gen.ts` (auto-generated)
- Routes: `src/routes/` using TanStack Router `createFileRoute`
- Server/API: add Hono routes in `src/entry-server.tsx`

## Conventions (Prefer)

- React components: use function declarations for named components
- Types: prefer `interface` for object shapes when reasonable
- Imports: `@/` alias or relative imports are both ok

## Environment Variables

- Server/SSR: `process.env.MY_VAR`
- Client: `import.meta.env.VITE_MY_VAR`

## Docs

- `AGENTS.md`
- `docs/ai/README.md`

---
> Source: [bskimball/tanstack-hono](https://github.com/bskimball/tanstack-hono) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-04 -->
