# deepseek-harness-ios

> Read `AGENTS.md` before proposing or changing code. It is the canonical project policy.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/deepseek-harness-ios/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Harness Mobile Copilot entry point

Read `AGENTS.md` before proposing or changing code. It is the canonical project policy.

- For a scoped module, read its nearest `AGENTS.md` before editing.
- Search `Vendor/`, `Dependencies/`, upstream Harness, and OpenMinis before creating a new abstraction.
- Use targeted `rg` plus small `sed` windows for large files; do not load whole aggregators.
- Run the smallest relevant tests first, then the repository validation required by `AGENTS.md`.
- Do not claim iPhone behavior is verified without device evidence. Never record secrets in code, tests, diffs, or diagnostics.

---
> Source: [liulingfei-1/deepseek-harness-ios](https://github.com/liulingfei-1/deepseek-harness-ios) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-28 -->
