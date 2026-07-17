# git-hygiene

> Commit and push verified relevant changes safely

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/git-hygiene/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Git Hygiene

- After successful checks, commit relevant code, documentation, and test changes, then push them to GitHub.
- Review `git status` and `git diff` before committing; stage only files related to the task.
- Never commit secrets, credentials, local data files, generated caches, or shortcuts.
- Do not force-push unless the user explicitly requests it and the target branch is safe.

---
> Source: [MyProEye-UG/MyProSole](https://github.com/MyProEye-UG/MyProSole) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-17 -->
