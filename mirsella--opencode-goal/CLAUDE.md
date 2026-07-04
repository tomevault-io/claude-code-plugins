# opencode-goal

> - npm publishing is handled by GitHub Actions in `.github/workflows/publish.yml`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/opencode-goal/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Notes

## npm publish workflow

- npm publishing is handled by GitHub Actions in `.github/workflows/publish.yml`.
- It runs automatically when a GitHub Release is published (`on.release.types: [published]`).
- It can also be triggered manually with `workflow_dispatch`.
- Manual runs default to `dry_run: true`, so pass `dry_run=false` to actually publish:
  `gh workflow run publish.yml -f dry_run=false`
- The workflow skips `npm publish` when the current `name@version` is already on npm.

---
> Source: [mirsella/opencode-goal](https://github.com/mirsella/opencode-goal) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-04 -->
