# read-docs-first

> Read project documentation before attempting any task

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/read-docs-first/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Read documentation first

- **Before attempting any task**, read the relevant project documentation so you understand setup, conventions, and existing patterns.
- Check at least:
  - **README** (root or package) — setup, scripts, architecture.
  - **CONTRIBUTING** (if present) — workflow, branching, PR expectations.
  - **Project-specific docs** — e.g. `docs/`, ADRs, or package READMEs for the area you’re changing.
- Use this to avoid reimplementing existing behavior, respect project conventions, and choose the right scripts and tooling (e.g. `pnpm` vs `npm`, which DB commands to run).

---
> Source: [SakaRicky/PumpApp](https://github.com/SakaRicky/PumpApp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-08 -->
