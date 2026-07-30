# safety-critical

> Critical safety limits for destructive, privileged, infrastructure, and environment-changing actions.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/safety-critical/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Safety Rules

CRITICAL: Safety rules override convenience.

NEVER run destructive or privileged commands without explicit user approval:

- `rm -rf`
- `sudo`
- `kubectl`
- `terraform`
- cloud provider CLI commands
- commands that delete data, reset history, rotate secrets, or mutate shared infrastructure

NEVER:

- Make infrastructure or environment changes unless the user explicitly asks for that exact action.
- Read or expose `.env`, secret files, credentials, full tokens, or password values unless the user explicitly approves a specific need.

MUST:

- Ask before any operation with irreversible or hard-to-reverse impact.
- Prefer read-only inspection commands when diagnosing infrastructure or environment issues.
- Explain the risk and reversal cost before proposing high-impact actions.

---
> Source: [kyungseo/ai-workflow-harness](https://github.com/kyungseo/ai-workflow-harness) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-29 -->
