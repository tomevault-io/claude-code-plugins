# mobgap

> - When the same skill name is available from multiple locations, always use the repository-local skill under `$REPO_ROOT/.agents/skills/`. Repository-local skills take precedence over user-global skills. Do not load or apply the corresponding skill from `$HOME/.agents/skills/` when a repository-local version exists.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mobgap/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Repository-local skills and refactoring

- When the same skill name is available from multiple locations, always use the repository-local skill under `$REPO_ROOT/.agents/skills/`. Repository-local skills take precedence over user-global skills. Do not load or apply the corresponding skill from `$HOME/.agents/skills/` when a repository-local version exists.
- Consider the repository's current publication state and backwards-compatibility requirements recorded in `.agents/refactor-policy.md` in all interactions.

---
> Source: [mobilise-d/mobgap](https://github.com/mobilise-d/mobgap) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-16 -->
