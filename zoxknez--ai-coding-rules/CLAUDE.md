# 20-security-privacy

> USE WHEN: handling auth, secrets, PII, input validation, or security-sensitive code.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/20-security-privacy/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Security & Privacy Rules

## Secrets & Credentials
- Never hard‑code API keys, passwords, or tokens.
- Use environment variables or secret managers.

## Input Validation
- Validate all external input (Zod/Pydantic or equivalent).
- Reject/normalize unexpected fields.

## Logging
- Never log PII or secrets.
- Scrub sensitive values before logging.

## Safety Stops
- If a change can cause data loss or a breaking change, stop and ask.

---
> Source: [zoxknez/ai-coding-rules](https://github.com/zoxknez/ai-coding-rules) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-02 -->
