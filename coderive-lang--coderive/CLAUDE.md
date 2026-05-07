# coderive

> - Keep `cod.ir.IRCodec.VERSION` at `1` during pre-version development.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/coderive/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Copilot Repository Instructions

## IR / Bytecode Versioning Rule (Pre-version Phase)

- Keep `cod.ir.IRCodec.VERSION` at `1` during pre-version development.
- Do **not** bump IR/bytecode format versions for internal format changes while we are not maintaining legacy compatibility yet.
- Only bump IR/bytecode version when maintainers explicitly decide to introduce compatibility/migration handling.

---
> Source: [coderive-lang/Coderive](https://github.com/coderive-lang/Coderive) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-07 -->
