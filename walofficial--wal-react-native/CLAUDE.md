# git-analysis

> Git information gathering for PR creation

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/git-analysis/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Git Analysis for PR Creation

## Required Commands

Execute these commands in sequence:

```bash
git status --porcelain                    # Check staged/unstaged files
git branch --show-current                 # Get current branch name
git log --oneline -10 --no-merges        # Recent commit messages
git remote get-url origin                 # Extract owner/repo
git diff --cached --name-status           # Staged changes summary
```

## Data Extraction

### Repository Info

```bash
# From: git remote get-url origin
# Extract: github.com/owner/repo.git -> owner="owner", repo="repo"
```

### Change Analysis

```bash
# From: git diff --cached --name-status
# A = Added, M = Modified, D = Deleted, R = Renamed
# Example: "M src/services/auth_service.py" -> Modified auth service
```

### Commit Messages

```bash
# From: git log --oneline -10 --no-merges
# Extract patterns: "feat:", "fix:", "refactor:", "docs:"
# Example: "feat: add JWT authentication" -> Feature addition
```

## Output Format

Return structured data:

```json
{
  "owner": "username",
  "repo": "repository-name",
  "head_branch": "feature/auth",
  "changes": ["M src/services/auth_service.py", "A tests/test_auth.py"],
  "commits": ["feat: add JWT authentication", "fix: handle edge cases"],
  "change_type": "feature"
}
```

---
> Source: [walofficial/wal-react-native](https://github.com/walofficial/wal-react-native) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-29 -->
