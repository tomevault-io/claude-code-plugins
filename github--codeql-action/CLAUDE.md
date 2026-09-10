# codeql-action

> The release process creates a cascade of PRs (`main` → `releases/vN`, then

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/codeql-action/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Merging release, mergeback, and backport PRs

The release process creates a cascade of PRs (`main` → `releases/vN`, then
`releases/vN` → `main` mergeback, then `releases/vN` → `releases/v(N-1)`
backport). These PRs reliably touch `CHANGELOG.md`, `src/defaults.json` /
`lib/defaults.json` (bundle/CLI version bump), and `src/api-compatibility.json`.

Such PRs **must be merged with a merge commit**. Never squash or rebase, as
that breaks the branch linkage the release automation relies on.

When arming auto-merge on these PRs, use `--merge` (e.g. `gh pr merge --merge`),
not `--squash` or `--rebase`.

---
> Source: [github/codeql-action](https://github.com/github/codeql-action) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-10 -->
