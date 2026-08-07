# portly

> - Always use Portly (`portly ...`) to start, stop, restart, inspect, or keep local development servers running.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/portly/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository instructions

## Development servers

- Always use Portly (`portly ...`) to start, stop, restart, inspect, or keep local development servers running.
- Start with `portly status --json`. Reuse a healthy managed server; if an in-scope server is running outside Portly, register it and use `portly take-over <project/server> --json`.
- Never launch persistent development servers directly, in the background, or through another supervisor.

---
> Source: [Melvynx/portly](https://github.com/Melvynx/portly) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-02 -->
