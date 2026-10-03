# no-git-stash

> Never git stash; preserve WIP with commits instead

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/no-git-stash/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# No git stash — commit instead

## Never

- `git stash`, `git stash push`, `git stash pop`, `git stash apply`, `git stash drop`
- Stashing to “clean the tree”, switch branches, or park unfinished EngPatch / name-input / bake work
- Advising the user to stash as the default way to save progress

## Always

- **Commit** unfinished or experimental work on the current branch (e.g. a ticket branch) so it stays in history and is recoverable
- If commit permission is unclear, **ask to commit** rather than stashing
- Use a normal commit message that marks WIP when needed (e.g. `WIP: title EngPatch badge — black-screen bisect`)
- Prefer a branch or WIP commit over stash when switching tasks

## Why

Stashed EngPatch / name-menu work (`deploy_title_engpatch_*`, `Eng_Patch.png`) was orphaned off Bleeding-Edge and missing from gold bake. Commits keep WIP on the branch.

Still follow the user’s commit gate: only create commits when they ask or when they explicitly want WIP preserved this way — never stash as a substitute.

---
> Source: [czyrustuazon/NewLovePlusPlusEngPatcher](https://github.com/czyrustuazon/NewLovePlusPlusEngPatcher) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-03 -->
