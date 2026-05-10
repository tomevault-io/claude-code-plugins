# 01-file-creation-protocol

> Strict protocol for creating new files to avoid duplication and drift

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/01-file-creation-protocol/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


### **Before creating any new file**
- Run an explicit directory listing of the target folder.
- Search the entire repo with fuzzy/name and content search for similar filenames and responsibilities.
- Check parent/related feature folders and existing imports/usages.
- Prefer editing existing files over adding new ones.
- If still unsure, ask for explicit approval before creating the file.

### **After creating a file**
- Add only focused content; avoid broad refactors.
- Ensure build passes; lint if applicable.
- Add tests/docs where meaningful.

---
> Source: [WilliamAvHolmberg/vibecodementor](https://github.com/WilliamAvHolmberg/vibecodementor) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
