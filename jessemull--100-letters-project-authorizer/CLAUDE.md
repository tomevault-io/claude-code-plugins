# 060-security

> Secrets, Cognito env, and fail-closed auth.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/060-security/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Security

Read `docs/SECURITY.md`.

- No hardcoded secrets or JWTs in source.
- Cognito IDs via env / CI / DefinePlugin only.
- Do not log full tokens.
- Auth failures must deny (throw `Unauthorized`).

---
> Source: [jessemull/100-letters-project-authorizer](https://github.com/jessemull/100-letters-project-authorizer) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-27 -->
