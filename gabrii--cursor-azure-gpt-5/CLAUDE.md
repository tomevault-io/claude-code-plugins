# lint-after-edit

> After finishing any big code changes, and before yielding to the user, run with your terminal tool the following comand:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/lint-after-edit/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Lint and Format After Edits

After finishing any big code changes, and before yielding to the user, run with your terminal tool the following comand:

```
source .venv/bin/activate && flask lint
```

This command will:
- Run **black** to automatically format the codebase.
- Run **flake8** to flag any remaining formatting or lint issues.

You don't need to preface it with /bin/bash -c, nor add | cat at the end. Just run it as is.

This ensures the codebase remains clean, consistent, and compliant with style guidelines after every edit.

---
> Source: [gabrii/Cursor-Azure-GPT-5](https://github.com/gabrii/Cursor-Azure-GPT-5) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-05 -->
