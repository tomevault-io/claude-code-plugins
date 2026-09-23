# isolade

> - `packages/server`: Hono API, chat backends, SQLite via Drizzle

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/isolade/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## Layout

- `packages/server`: Hono API, chat backends, SQLite via Drizzle
- `packages/web`: the React + Tailwind frontend
- `packages/shared`: types and protocol shared by both
- `packages/sandbox`: microVM runtime, runs in-process inside the server
- `app`: Tauri (Rust) desktop shell

## Running it

`bun run dev` starts everything in one terminal: UI on http://localhost:5173,
API on `:3000`.

`bun run check` runs format, lint, typecheck and test.

---
> Source: [isolade/isolade](https://github.com/isolade/isolade) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-23 -->
