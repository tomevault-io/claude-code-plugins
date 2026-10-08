# lavamilk-template

> For every task that writes, modifies, fixes, refactors, tests, reviews, scaffolds, or designs code, invoke and follow `$code-boundary-standards` before making code changes.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/lavamilk-template/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository instructions

For every task that writes, modifies, fixes, refactors, tests, reviews, scaffolds, or designs code, invoke and follow `$code-boundary-standards` before making code changes.

See [docs/architecture.md](docs/architecture.md) for entry points, dependency rules, runtime exceptions and verification commands. Run `npm run check`; for routing, persistence or HTTP changes also run the relevant browser and MySQL integration tests. `npm run check:all` runs the full suite.

---
> Source: [lavamilkTeam/lavamilk.template](https://github.com/lavamilkTeam/lavamilk.template) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-06 -->
