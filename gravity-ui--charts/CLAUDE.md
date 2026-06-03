# charts

> - Use `interface` instead of `type` for object shape declarations where possible. Fall back to `type` only when necessary (unions, intersections, mapped types, primitives, tuples).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/charts/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# TypeScript conventions

- Use `interface` instead of `type` for object shape declarations where possible. Fall back to `type` only when necessary (unions, intersections, mapped types, primitives, tuples).

# Plugin architecture

- Series-specific behavior must live in the plugin, not in shared hooks or utilities. Never add a hardcoded `Set`, `switch`, or constant keyed on series type string in shared code — add a field to `SeriesPlugin` and let each plugin declare its own behavior.

---
> Source: [gravity-ui/charts](https://github.com/gravity-ui/charts) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-02 -->
