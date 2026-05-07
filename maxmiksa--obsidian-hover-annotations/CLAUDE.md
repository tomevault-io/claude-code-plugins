# obsidian-hover-annotations

> - Symptom: Complex `node -e "..."` commands fail in PowerShell with parser errors before Node runs.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/obsidian-hover-annotations/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Local Notes

## PowerShell Inline Node
- Symptom: Complex `node -e "..."` commands fail in PowerShell with parser errors before Node runs.
- Cause: PowerShell re-parses nested quotes, brackets, and backticks inside inline JavaScript.
- Fix: Prefer a here-string piped to Node, for example `@'...js...'@ | node`, instead of `node -e`.

---
> Source: [MaxMiksa/Obsidian-Hover-Annotations](https://github.com/MaxMiksa/Obsidian-Hover-Annotations) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-02 -->
