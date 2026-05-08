# git-workflow

> Git Workflow and Configuration for AGB SDK

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/git-workflow/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Git Configuration

## User Information
- **User Name**: xiangting.cxt
- **User Email**: xiangting.cxt@alibaba-inc.com

## Repository Information
- **Remote URL**: it@gitlab.alibaba-inc.com:InnoArchClub/ai-sdk-oversea.git
- **Push Command**: `git push origin HEAD:refs/for/master`

## Workflow
1. Ensure all changes are staged.
2. Commit with semantic commit messages.
3. Push using the specific Gerrit refspec `refs/for/master` to trigger code review.

---
> Source: [agbcloud/agbcloud-sdk](https://github.com/agbcloud/agbcloud-sdk) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-04 -->
