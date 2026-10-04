# conventional-commits

> Commit messages must use Conventional Commits with lowercase subjects

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/conventional-commits/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Conventional commits

When writing any git commit message (or commit title for the user):

- Use [Conventional Commits](https://www.conventionalcommits.org/): `<type>(optional-scope): <subject>`
- Entire subject (and scope) in **lowercase**
- Imperative, no trailing period, ≤ ~72 chars
- Types: `feat` `fix` `refactor` `perf` `test` `docs` `style` `build` `ci` `chore` `revert`

Examples: `feat(api): add context pack`, `fix(jobs): renew lease heartbeat`

Apply the personal skill `conventional-commits` whenever you draft or run a commit.

---
> Source: [gonnafaraway/kaiban](https://github.com/gonnafaraway/kaiban) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-04 -->
