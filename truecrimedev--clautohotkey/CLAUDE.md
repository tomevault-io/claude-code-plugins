# 30-text-processing

> description: Text processing, escapes, and regex (PCRE)

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/30-text-processing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

---
description: Text processing, escapes, and regex (PCRE)
alwaysApply: false
---

Rules
- Backtick-only escapes; canonical sequences: `` `, `", `', `n, `r, `t, `s, `b, `v, `a, `f, `:, `;.
- Built-ins: `Trim/StrUpper/StrLower/StrReplace/StrSplit/InStr/SubStr`.
- Regex PCRE options: `i/m/s/x`; escape literals; prefer named groups when helpful.

References
- Modules reference: `Modules/Module_TextProcessing.md`, `Modules/Module_Escapes.md`
- Additional examples: `AHK_Notes/Concepts/string-handling-in-ahk-v2.md`

---
> Source: [TrueCrimeDev/ClautoHotkey](https://github.com/TrueCrimeDev/ClautoHotkey) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
