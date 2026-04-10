# apex

> This is a monorepo with:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/apex/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Cenna Platform — Root Rules

This is a monorepo with:
- `backend/` — FastAPI + SQLAlchemy + Alembic (Python 3.12)
- `frontend/` — React + Vite + TypeScript + Tailwind CSS v4 + shadcn/ui

## General
- Follow existing code style and conventions in each sub-project.
- Never modify `.env` files directly; update `.env.example` instead.
- All new features go on dedicated `feature/*` branches.
- **Local dev:** Postgres + `uv` / `npm` (see root `README.md`). **Container deploy:** `scripts/docker-compose.yml` (see README “Deploy”).
- Backend runs on port 8100, frontend on port 3100.

## See also
- `backend/.cursorrules` — Backend-specific rules, **including RBAC & permission enforcement**
- `frontend/.cursorrules` — Frontend brand, UX, and code guidelines

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/cennahq) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
