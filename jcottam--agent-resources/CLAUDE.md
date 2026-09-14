# agent-resources

> This repository contains agent skills and Cursor rules.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agent-resources/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Resources

This repository contains agent skills and Cursor rules.

## Contributing

- Skills live in `skills/<category>/<skill-name>/SKILL.md`.
- Each `SKILL.md` has YAML frontmatter with `name` and `description`, followed by the skill body in markdown.
- When adding a skill, also add it to `.claude-plugin/plugin.json` and the reference table in `README.md`.
- Rules live in `rules/` as `.mdc` files with YAML frontmatter (`description`, `globs`, `alwaysApply`).
- Keep skills focused on a single concern. Prefer short, composable skills over large monolithic ones.

---
> Source: [jcottam/agent-resources](https://github.com/jcottam/agent-resources) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-14 -->
