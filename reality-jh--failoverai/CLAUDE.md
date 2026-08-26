# failoverai

> - Keep this repository independent. Do not copy credentials, data, branding, prompts, domains, or configuration from reference projects.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/failoverai/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# FailoverAI contributor instructions

- Keep this repository independent. Do not copy credentials, data, branding, prompts, domains, or configuration from reference projects.
- PostgreSQL is authoritative for jobs, idempotency, leases, attempts, events, and final results.
- Fake providers are the only providers in the reference implementation.
- Prefer the smallest implementation that preserves safety, fencing, and observability.
- Run backend tests, frontend typecheck/build, Compose health checks, CodeGraph sync, and release scans before claiming completion.
- Never log prompts, raw idempotency keys, secrets, or provider payloads.

---
> Source: [Reality-JH/FailoverAI](https://github.com/Reality-JH/FailoverAI) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-25 -->
