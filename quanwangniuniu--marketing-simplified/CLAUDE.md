# security-privacy

> Security and privacy (no secrets in logs, validate input, least privilege).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/security-privacy/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Security & privacy (always)

- **Never log secrets** (tokens, passwords, full headers).
- **Validate untrusted input** on the backend (treat everything from the client as hostile).
- **Least privilege**: permissions/roles should default to "deny" unless explicitly allowed.

---
> Source: [quanwangniuniu/marketing-simplified](https://github.com/quanwangniuniu/marketing-simplified) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-13 -->
