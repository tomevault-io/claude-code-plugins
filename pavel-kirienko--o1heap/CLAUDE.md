# o1heap

> Please read all Markdown documents at the top level, and all source files in the `o1heap/` directory.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/o1heap/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Instructions for AI agents

Please read all Markdown documents at the top level, and all source files in the `o1heap/` directory.
Do not use search, read files whole.

When building the code, don't hesitate to use multiple jobs to use all CPU cores.
Do not create temporary build or test artifacts in the project root; create dedicated build dirs for that instead.

Run all tests in debug build to ensure that all assertion checks are enabled.

It is best to use Clang-Format to format the code when done editing.

---
> Source: [pavel-kirienko/o1heap](https://github.com/pavel-kirienko/o1heap) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-29 -->
