# backend-venv

> Backend environment setup and activation

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/backend-venv/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Backend Env Setup

* Venv location: `backend/.venv`
* If missing, create it:

```bash
cd backend
uv venv || python3 -m venv .venv
```

* Activate:

```bash
source .venv/bin/activate
```

* Install deps (also creates venv if needed):

```bash
uv sync --native-tls
```

* Use uv when installing dependencies.
* Add deps: `uv add <pkg>` • Deactivate: `deactivate`
  

---
> Source: [MylesThomas/betting](https://github.com/MylesThomas/betting) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-17 -->
