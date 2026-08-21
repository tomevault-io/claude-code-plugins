# transformer-explorer

> Interactive textbook for the 2017 Transformer paper (*Attention Is All You Need*).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/transformer-explorer/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent notes

Interactive textbook for the 2017 Transformer paper (*Attention Is All You Need*).

## Stack

- **TanStack Start** — SSR, file-based routes under `src/routes/`
- **React 19** + **Tailwind CSS 4** + **shadcn/ui** components
- **Vite** + **Nitro** for build/deploy

## Conventions

- Chapter metadata lives in `src/lib/chapters.ts`; each chapter is a route in `src/routes/`
- Interactive visualizations are in `src/components/viz/`
- Math helpers: `src/lib/tmath.ts`
- Custom SSR entry: `src/server.ts` wraps TanStack Start's server entry for error pages
- Path alias: `@/*` → `src/*`

## Dev commands

```bash
bun install
bun run dev      # http://localhost:3000
bun run build
bun run lint
```

---
> Source: [byteom/Transformer-Explorer](https://github.com/byteom/Transformer-Explorer) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-21 -->
