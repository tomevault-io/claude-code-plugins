# jiraps

> This file applies to all `.ps1` files. It references shared rules.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/jiraps/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# PowerShell File Rules (GitHub Copilot)

This file applies to all `.ps1` files. It references shared rules.

**Canonical source**: [.github/ai-context/powershell-rules.md](../ai-context/powershell-rules.md)

## Quick Reference

1. **Cloud AND Data Center** — all changes must work on both Jira deployment types
2. **User Identity** — `accountId` for Cloud, `username`/`name` for DC
3. **ADF** — only use `ConvertTo-ADF`/`ConvertFrom-ADF` for Cloud
4. **REST calls** — always go through `Invoke-JiraMethod`
5. **Tests required** — every function needs `.Unit.Tests.ps1`
6. **Single-test loop** — run individual unit tests directly with `Invoke-Pester Tests/**`; use `Invoke-Build -Task Build, Test` for full-suite validation

For full rules, read `.github/ai-context/powershell-rules.md`.

---
> Source: [AtlassianPS/JiraPS](https://github.com/AtlassianPS/JiraPS) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-27 -->
