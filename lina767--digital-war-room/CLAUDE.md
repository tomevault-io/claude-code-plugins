# project-overview

> Digital War Room – Projekt-Überblick und Konventionen

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/project-overview/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Digital War Room – Projekt-Überblick

## Stack
- **Backend:** Python 3, FastAPI, Agents (FININT, SIGINT, NEWS, GEOINT, SOCMINT, TECHINT)
- **Frontend:** React, TypeScript, Vite, Tailwind
- **API:** REST unter `/api/*`, optional WebSocket

## Struktur
- `backend/` – FastAPI-App, `main.py`, `agents/`, `api/`
- `src/` – React-App, `pages/`, `components/`, `hooks/`
- API-Keys und Secrets in `backend/.env` (nicht committen); Frontend-Env in Projektroot `.env` (z. B. `VITE_API_URL`)

## Konventionen
- Backend-Agents liefern einheitlich ein Dict mit Score, Summary und fachlichen Listen (z. B. `aircraft`, `ships`, `key_findings`).
- Bei fehlgeschlagener LLM-Antwort: Fallback mit direkten Tool-Aufrufen und berechnetem Score, damit nie leere Daten zurückgegeben werden.
- Kommentare und Nutzer-Texte dürfen Deutsch oder Englisch sein.

---
> Source: [lina767/digital-war-room](https://github.com/lina767/digital-war-room) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-28 -->
