# registry-consistency

> Keep registry entries in sync with actual module locations

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/registry-consistency/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Registry entries map string keys to fully qualified Python import paths.
When modifying registry files:
- Verify each path actually resolves to the correct class
- Check that class names match the import path
- Test with get_*_class() to confirm resolution works
See constraints #1-#4 in .agents/knowledge/constraints.md.

---
> Source: [X-GenGroup/Flow-Factory](https://github.com/X-GenGroup/Flow-Factory) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
