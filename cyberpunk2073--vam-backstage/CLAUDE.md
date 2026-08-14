# fetch-github-prs

> How to fetch GitHub pull requests with plain git (no gh CLI). Use when checking out, reviewing, or fetching a PR by number.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/fetch-github-prs/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Fetch GitHub PRs with plain git

`origin` is configured with `+refs/pull/*/head:refs/remotes/origin/pr/*`, so `git fetch origin` mirrors every PR to `origin/pr/<N>`. Check one out with `git switch -c pr-3 origin/pr/3`.

Plain git fetches PR commits only — for metadata (title, comments, checks, open-PR list) hit the REST API: `https://api.github.com/repos/cyberpunk2073/vam-backstage/pulls`.

---
> Source: [cyberpunk2073/vam-backstage](https://github.com/cyberpunk2073/vam-backstage) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-13 -->
