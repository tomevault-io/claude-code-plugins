# pr-comments

> goal: address PR comments

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pr-comments/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

goal: address PR comments
- get PR comments
```bash
# Find PR for current branch
gh pr list --head $(git branch --show-current) | cat

# Get inline comments (most important)
gh api repos/:owner/: repo/pulls/PR_NUMBER/comments —jq '.[] | {author: user. login, body: .
body, path: -path, line: . line}' | cat

# Get review comments if needed
gh api repos/: owner/: repo/pulls/PR_NUMBER/reviews --jq '.[] | select(body != "') | {author: .
user. login, body: "body}' | cat
```

- if no PR exists, abort
- suggest fixes for each comment
- always use '| cat'

---
> Source: [greyhaven-ai/sygaldry](https://github.com/greyhaven-ai/sygaldry) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-15 -->
