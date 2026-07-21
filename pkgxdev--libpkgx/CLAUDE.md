# libpkgx

> Public shared runtime library used across multiple pkgx tools.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/libpkgx/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS: libpkgx

Public shared runtime library used across multiple pkgx tools.

## Core Commands

- `deno task test`
- `deno lint`
- `deno task typecheck`

## Always Do

- Treat public APIs as compatibility-sensitive.
- Add or update tests for changed contract behavior.
- Note downstream impact on `pkgm`, `pkgo`, `dev`, `brewkit`, and `mcp`.

## Ask First

- Breaking API or behavior changes.
- Dependency upgrades with broad runtime impact.

## Never Do

- Never merge contract changes without compatibility notes.
- Never bypass tests on shared utility hotspots.

---
> Source: [pkgxdev/libpkgx](https://github.com/pkgxdev/libpkgx) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-20 -->
