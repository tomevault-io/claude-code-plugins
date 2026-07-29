# contextrie

> - Follow `CONTRIBUTING.md` for dev commands and conventions

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/contextrie/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Core Guidelines

- Follow `CONTRIBUTING.md` for dev commands and conventions
- Keep types in `core/types`; keep agent contracts in `core/agents`
- Avoid IO in core contracts
- After changes, update relevant docs to keep them in sync
- When the user says `commit`, stage each diff individually, group related diffs into relevant commits, write a one-line commit message for each group, and commit them in that order

---
> Source: [feuersteiner/contextrie](https://github.com/feuersteiner/contextrie) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-21 -->
