# mdto

> - `client/`: React + TanStack Start frontend (routes, components, hooks, client libs).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mdto/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Project Structure & Module Organization
- `client/`: React + TanStack Start frontend (routes, components, hooks, client libs).
- `server/`: Cloudflare Workers backend (routes, db, server utilities).
- `shared/`: Cross-cutting utilities and templates (markdown pipeline, themes).
- `public/`: Static assets served by the client build.
- `migrations/`: D1/Drizzle database migrations.
- `scripts/`: Build/deploy helpers (template hash, copy output).

## Build, Test, and Development Commands
- `pnpm build`: Generate template hash, type-check, build client, and copy output.
- `pnpm lint` / `pnpm lint:fix`: Run Biome checks (and auto-fix).
- `pnpm test`: Run Vitest with the Cloudflare Workers pool.

## Working Rules
- After making code changes, run `pnpm lint:fix` before finishing unless the user explicitly says not to.

---
> Source: [hjinco/mdto](https://github.com/hjinco/mdto) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-21 -->
