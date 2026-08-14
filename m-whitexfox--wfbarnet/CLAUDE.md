# wfbarnet

> - Treat all Markdown and Chinese text files in this repository as UTF-8.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/wfbarnet/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository Instructions

- Treat all Markdown and Chinese text files in this repository as UTF-8.
- On Windows PowerShell, read text files with explicit encoding, for example `Get-Content -Encoding UTF8`.
- Do not assume a file is corrupted just because default PowerShell output shows mojibake; verify with explicit UTF-8 decoding before editing.
- Preserve UTF-8 when editing documentation. Prefer LF unless the existing file requires otherwise.

---
> Source: [M-WhiteXFox/WFBARNet](https://github.com/M-WhiteXFox/WFBARNet) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-13 -->
