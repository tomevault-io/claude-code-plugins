# mlx-ruby

> 1. Always run tests after making changes.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mlx-ruby/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

### Mandatory Test Execution

1. Always run tests after making changes.
2. At minimum, run the most targeted tests for touched files/features.
3. For broad or cross-cutting changes, run the full suite before considering work complete.
4. If any test cannot be run, explicitly document which test was skipped and why.

## Completion Criteria

Treat work as complete only when all are true:

1. Phase checklist items are updated.
2. New/updated tests are green.
3. Regressions in touched areas are checked.
4. PRD status reflects reality (`Completed` only when fully done).

---
> Source: [skryl/mlx-ruby](https://github.com/skryl/mlx-ruby) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-19 -->
