# laravel-salesforce

> "composer.json": true,

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/laravel-salesforce/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

{
    "filePatterns": {
        "*.php": true,
        "composer.json": true,
        "*.blade.php": true,
        "config/*.php": true,
        "database/migrations/*.php": true,
        "routes/*.php": true,
        "tests/*.php": true
    },
    "languageFeatures": {
        "references": true,
        "completion": true,
        "diagnostics": true,
        "documentSymbols": true,
        "documentFormatting": true,
        "hover": true
    },
    "ignorePatterns": [
        "vendor/**",
        "node_modules/**",
        "storage/**",
        "bootstrap/cache/**"
    ]
}

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/antogkou) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
