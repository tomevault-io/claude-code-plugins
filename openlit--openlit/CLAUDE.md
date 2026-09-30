# openlit

> These instructions supplement the repository-root `AGENTS.md`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/openlit/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# OTLP receiver instructions

These instructions supplement the repository-root `AGENTS.md`.

- This is an independent Go module. Validate with `go test ./...`.
- Do not log API keys, Authorization headers, or ClickHouse passwords.
- Tenant writes must stay isolated by OpenLIT API key → organisation → project → environment → DatabaseConfig.

---
> Source: [openlit/openlit](https://github.com/openlit/openlit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-30 -->
