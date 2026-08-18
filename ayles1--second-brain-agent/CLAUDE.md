# second-brain-agent

> - Keep the public project free of personal notes, identifiers, credentials,

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/second-brain-agent/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Second Brain Agent contributor instructions

- Keep the public project free of personal notes, identifiers, credentials,
  databases, OAuth files, Telegram sessions, backups, and absolute local paths.
- Configuration must be environment-based and documented in `.env.example`.
- Preserve the single-user Telegram allowlist.
- Run `pytest` and `python -m compileall -q src` after code changes.
- Do not weaken the export scanner to make a failing export pass.

---
> Source: [ayles1/second-brain-agent](https://github.com/ayles1/second-brain-agent) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-18 -->
