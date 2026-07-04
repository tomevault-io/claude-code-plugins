# protected-files

> Hard rule — do not edit generated spec baselines or local credential files.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/protected-files/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Protected files

Refuse edits to these paths. Explain why, then stop.

- **`tools/spec/*.json`** — generated baselines (Apple/Google/Samsung). Refresh via `castor spec:baseline:{google|apple|samsung}`, only after confirming intentional drift (see `refresh-wallet-spec`). Hand-edits hide real drift.
- **`**/.env.local`** — local credentials for `examples/`. Human-only. If new fields are needed, update the committed `.env` template and tell the user what to fill in.

---
> Source: [jolicode/wallet-kit](https://github.com/jolicode/wallet-kit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-04 -->
