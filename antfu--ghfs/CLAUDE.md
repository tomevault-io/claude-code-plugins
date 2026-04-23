# ghfs

> - CLI related logics, usage of `@clack/prompts`, `console.log` can only be under `src/cli/`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ghfs/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Rules

- CLI related logics, usage of `@clack/prompts`, `console.log` can only be under `src/cli/`
- GitHub related logics, usage of `octokit` can only be under `src/providers/github/`
- Pure/simple functions should better be under `src/utils/` and be tested alongside.
- Avoid duplicating logics, refactor them to reuse.
- Always use `pathe` instead of `node:path`
- At this moment, we don't care about breaking changes at all, don't worry about migration or backward compatibility.

---
> Source: [antfu/ghfs](https://github.com/antfu/ghfs) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-21 -->
