# agentprobe

> Provider implementation pipeline and parsing rules

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agentprobe/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Provider Pipeline

- Follow provider contract shape exactly: `discover -> read -> normalize`.
- `discover` must return `{ inputs, watchPaths, warnings }`.
- `read` must return raw records + health; do not canonicalize here.
- `normalize` must output canonical `{ agents, health }`.
- Parse external data defensively (`safeParse`), accumulate warnings, continue on bad records.
- Keep status names consistent: `running | idle | completed | error`.
- Put shared tunables in `constants.ts`; keep file-local constants at module top.
- Prefer options interfaces with defaults via `??`; use explicit `false` to disable optional features.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/vtemian)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/vtemian)
<!-- tomevault:4.0:claude_md:2026-04-09 -->
