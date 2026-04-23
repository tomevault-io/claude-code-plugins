# rainbot

> React dashboard — Vite, components, API usage

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/rainbot/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# UI (React Dashboard) Rules

Vite + React app in `ui/`. Deploy separately (e.g. `ui/railway.json`). Dev: `yarn workspace @rainbot/ui dev`.

## API

- API client and types in `ui/src/lib/api.ts`, `ui/src/types/`
- Authenticated requests use session; check `ui/src/stores/authStore.ts` for auth state

## Components

- `ui/src/components/` — shared components
- `ui/src/pages/` — page-level components
- `ui/src/hooks/` — custom hooks

## Build

- `yarn build:ui` from root when deploying UI

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/Connor-Adams) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
