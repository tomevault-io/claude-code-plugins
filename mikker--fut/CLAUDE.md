# fut

> - `CHANGELOG.md` is user-facing. Only note changes users will notice; omit internal work.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/fut/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project notes

## Changelog

- `CHANGELOG.md` is user-facing. Only note changes users will notice; omit internal work.
- Keep entries brief and update `Unreleased` as user-facing tasks finish.
- Before releasing, consolidate related entries, move them under the new version, and start a fresh `Unreleased` section.

## Release

- From a clean, synchronized `main`, run `mise run release`.
- It tests, advances the `0.x` version, tags and pushes. GitHub builds both macOS binaries, publishes the release, and updates `mikker/homebrew-tap`.

---
> Source: [mikker/fut](https://github.com/mikker/fut) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-06 -->
