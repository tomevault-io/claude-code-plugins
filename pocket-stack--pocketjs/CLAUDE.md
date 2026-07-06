# pocketjs

> - After completing and validating a code or documentation change, publish it as a draft pull request before treating the work as ready for review or merge.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pocketjs/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository Instructions

- After completing and validating a code or documentation change, publish it as a draft pull request before treating the work as ready for review or merge.
- If the user also asks to merge the change, open the draft pull request first, then mark it ready and merge it after the relevant checks pass.
- Name pull requests (and the branch's primary commit) using the Conventional Commits format — `type(scope): summary`, e.g. `feat(gallery): …`, `fix: …`, `docs: …`, `refactor: …`.
- Keep PocketJS examples explicit about API ownership: import PocketJS runtime, host components, lifecycle, input, and animation APIs from `@pocketjs/framework/*`; import Solid primitives and control flow directly from `solid-js`.

---
> Source: [pocket-stack/pocketjs](https://github.com/pocket-stack/pocketjs) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-06 -->
