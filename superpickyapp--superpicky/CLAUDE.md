# superpicky

> Follow project rules in:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/superpicky/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Cursor legacy rules file

Follow project rules in:

- `scripts_dev/AI_CODING_RULES.md`
- `.cursor/rules/superpicky-core-rules.mdc`

Key constraints:

- UTF-8 safety, avoid Chinese mojibake.
- ExifTool non-ASCII metadata via UTF-8 temp-file redirection.
- Cross-platform Windows/macOS compatibility.
- Packaged CUDA issues: diagnose packaging/runtime first.
- Keep Windows Torch/CUDA packaging with UPX disabled unless re-validated.

---
> Source: [superpickyapp/Superpicky](https://github.com/superpickyapp/Superpicky) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-25 -->
