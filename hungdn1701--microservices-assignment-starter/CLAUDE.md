# microservices-assignment-starter

> Microservices university assignment. Technology-agnostic.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/microservices-assignment-starter/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GitHub Copilot — Custom Instructions
# Docs: https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions
#
# Full project rules and context: .ai/AGENTS.md
# This file contains a summary for Copilot. Edit .ai/AGENTS.md for the source of truth.

## Project

Microservices university assignment. Technology-agnostic.
Run with: `docker compose up --build`

## Key Rules

- Every service exposes `GET /health` → `{"status": "ok"}`
- Services communicate via Docker Compose DNS (service names, not localhost)
- API specs in `docs/api-specs/*.yaml` (OpenAPI 3.0)
- Use environment variables for config — never hardcode secrets
- Code runs inside Docker containers
- Follow OpenAPI specs when implementing endpoints

---
> Source: [hungdn1701/microservices-assignment-starter](https://github.com/hungdn1701/microservices-assignment-starter) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-17 -->
