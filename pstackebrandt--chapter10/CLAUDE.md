# chapter10

> Guidelines for creating PowerShell scripts

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/chapter10/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# PowerShell Scripting Guidelines

Prefer PowerShell 7 commands for Windows 11, not Bash syntax.
Prefer PowerShell-native approaches over cmd.exe commands.

## Command Syntax
- Use PowerShell cmdlets: `Get-ChildItem` (not `ls`), `Set-Location` (not `cd`)
- Flags use single hyphen (`-Force`)
- Command separation: `;` (not `&&`)

## Path Handling
- Use backslashes in Windows paths: `C:\Users\`
- Use `Join-Path` for path construction
- Always quote paths with spaces

## Variables and Environment
- Variables: `$variable`, string interpolation: `"$(...)"`
- Environment variables: `$env:VARIABLE`

## Input/Output
- Piping: `|` (with proper object handling)
- Redirection: `>`, `>>`, `2>`

## Error Handling
- Check `$LASTEXITCODE` after external commands
- Use try/catch blocks for risky operations
- Log errors with `Write-Error` to stderr

## Git Bash Integration
- Use `Invoke-GitBash.ps1` for bash scripts
- Handle path conversions
- Propagate exit codes correctly

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/pstackebrandt) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
