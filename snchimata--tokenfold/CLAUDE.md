# tokenfold

> $rawInput = [Console]::In.ReadToEnd()

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tokenfold/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# TaskResume Hook
# PowerShell template for Windows hook execution.

try {
    $rawInput = [Console]::In.ReadToEnd()
    if ($rawInput) {
        $null = $rawInput | ConvertFrom-Json
    }
} catch {
    Write-Error "[TaskResume] Invalid JSON input: $($_.Exception.Message)"
}

@{
    cancel = $false
    contextModification = ""
    errorMessage = ""
} | ConvertTo-Json -Compress

---
> Source: [snchimata/tokenfold](https://github.com/snchimata/tokenfold) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-07 -->
