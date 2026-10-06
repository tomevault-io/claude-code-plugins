# gwz-cli

> Follow the root `AGENTS.md` rules.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/gwz-cli/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS

Follow the root `AGENTS.md` rules.

- Work TDD-first: failing test, implementation, green tests, then refactor.
- Keep CLI behavior thin; workspace semantics belong in `gwz-core`.
- Do not call Git directly from the CLI.
- Do not read or write GWZ artifacts directly from the CLI.

---
> Source: [owebeeone/gwz-cli](https://github.com/owebeeone/gwz-cli) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-05 -->
