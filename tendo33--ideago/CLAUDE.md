# backend-python-service-standards

> Backend service/API standards for Python projects using typed models, clear layering, and reliable verification.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/backend-python-service-standards/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

- For backend API/service work, follow `ai_docs/BACKEND_STANDARDS.md`. See `ai_docs/AI_TOOLING_STANDARDS.md` for full docs index.
- Use layered boundaries: API -> service -> repository -> domain.
- Keep route handlers thin; place business logic in service layer.
- Use Pydantic v2 models for request/response and validation.
- Keep persistence logic in repository layer and use explicit transaction boundaries.
- Handle errors explicitly and return structured, stable error payloads.
- Avoid logging secrets, tokens, passwords, or sensitive personal data.
- Add or update tests for new behavior and bug fixes.
- Run `uv run ruff check .`, `uv run ruff format --check .`, and `uv run pytest` before completion.

---
> Source: [Tendo33/IdeaGo](https://github.com/Tendo33/IdeaGo) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
