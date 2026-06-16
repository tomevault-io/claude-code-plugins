# temper-pack-git

> Temper quality pack: git

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/temper-pack-git/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Git Pack

**Version:** 1.0.0
**Last Updated:** 2025-03-09

## Quality Rules (WARN if violated)
- Commit messages must follow Conventional Commits format
- Commits should be atomic (one logical change per commit)
- Never commit directly to main/master branch
- Branch names should be descriptive: feature/{ticket}-{description}

## Conventions (SUGGEST improvements)
- Include ticket/issue reference in commit message body
- Keep commits small and focused
- Write commit body explaining WHY, not WHAT
- Delete branches after merging

---
> Source: [galando/temper](https://github.com/galando/temper) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
