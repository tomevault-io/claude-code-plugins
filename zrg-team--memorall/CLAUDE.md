# memorall

> - Protected branch names are `main`, `master`, and `develop`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/memorall/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository agent instructions

## Git branch naming

- Protected branch names are `main`, `master`, and `develop`.
- Every task branch must use `<type>/<lowercase-kebab-case-description>`.
- Allowed types are `feat`, `fix`, `chore`, `refactor`, `test`, `docs`, `style`, `perf`, `build`, `ci`, `revert`, `release`, and `hotfix`.
- Dependency upgrades use `chore/`, for example `chore/upgrade-web-extension-desktop-dependencies`.
- Names with other prefixes, uppercase letters, underscores, repeated hyphens, or nested path segments are invalid.
- Husky and CI enforce the complete naming standard; do not bypass `check:branch-name`.

---
> Source: [zrg-team/memorall](https://github.com/zrg-team/memorall) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-19 -->
