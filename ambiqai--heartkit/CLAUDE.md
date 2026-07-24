# heartkit

> Repo-specific notes for automation and maintenance:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/heartkit/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS

Repo-specific notes for automation and maintenance:
- Python target is 3.12; use `uv sync` for installs and `uv run pytest tests/` for tests.
- Docs use MkDocs Material; preview with `mkdocs serve` and keep headings plain Markdown (no span wrappers).
- Prefer `rg` for searches and avoid touching binary assets unless requested.
- Commit messages follow Conventional Commits (e.g., `feat: ...`, `fix: ...`, `chore: ...`).

---
> Source: [AmbiqAI/heartkit](https://github.com/AmbiqAI/heartkit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-21 -->
