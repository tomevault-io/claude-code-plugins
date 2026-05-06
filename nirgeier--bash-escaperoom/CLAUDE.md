# bash-escaperoom

> **NEVER perform any git operations without explicit user confirmation.**

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/bash-escaperoom/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GitHub Copilot Instructions

## ⚠️ CRITICAL: No Automatic Git Operations

**NEVER perform any git operations without explicit user confirmation.**

This includes:
- `git commit`
- `git push`
- `git add`
- `git merge`
- `git rebase`
- `git reset`
- `git stash`
- Any other command that modifies git history or pushes to remote

### What to do instead

After making file changes, **stop and show the user what was changed**.  
Only run git commands when the user explicitly says something like:
- "commit this"
- "push the changes"
- "go ahead and push"

---
> Source: [nirgeier/Bash-EscapeRoom](https://github.com/nirgeier/Bash-EscapeRoom) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
