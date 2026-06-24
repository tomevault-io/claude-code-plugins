# llvm-snippy

> When performing a code review, pay close attention to code modifying a function's

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/llvm-snippy/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

When performing a code review, pay close attention to code modifying a function's
control flow. Could the change result in the corruption of performance profile
data? Could the change result in invalid debug information, in particular for
branches and calls?

---
> Source: [LLVM-Snippy/llvm-snippy](https://github.com/LLVM-Snippy/llvm-snippy) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-24 -->
