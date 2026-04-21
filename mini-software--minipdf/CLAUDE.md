# minipdf

> - .NET security policy

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/minipdf/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

- English
- No Emoji
- .NET security policy
- System can't auto git push 

## Issue Summary Workflow
When user says "summary on issue #N", use `gh issue comment N --body-file -` 
to post a summary of completed work to the GitHub issue.

## Testing Workflow

### Unit Tests
```powershell
dotnet test tests/MiniPdf.Tests
```



### Single File / Filtered Run
```powershell
scripts/Run-Benchmark.ps1 -Filter "border"           # only cases containing "border"
scripts/Run-Benchmark_docx.ps1 -Filter "heading"
scripts/Run-Benchmark_issues.ps1 -Filter "sa8000"    # -Filter is mandatory for issues
```

---
> Source: [mini-software/MiniPdf](https://github.com/mini-software/MiniPdf) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
