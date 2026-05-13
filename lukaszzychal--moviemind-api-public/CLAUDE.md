# 050-security-baseline

> - Never add/commit secrets. Prefer environment variables. Never log secrets.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/050-security-baseline/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Security baseline

- Never add/commit secrets. Prefer environment variables. Never log secrets.
- Validate input, enforce auth/authorization, and consider rate limiting for public endpoints.
- If output/logs may contain sensitive data: stop and warn.
- For AI-related features: treat user input as untrusted (prompt injection). Keep strict output formats.

---
> Source: [lukaszzychal/moviemind-api-public](https://github.com/lukaszzychal/moviemind-api-public) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-13 -->
