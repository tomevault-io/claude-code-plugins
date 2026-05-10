# 01-diagnose-before-fixing

> Enforce diagnostic-first workflow using React Debugger MCP

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/01-diagnose-before-fixing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


When you are helping debug React bugs, follow this workflow:

1. **Diagnose before editing.**
2. **Do not** propose or change code before using the React Debugger tools:
   - `tools/call subscribe` → capture `fid`
   - `tools/call nextEvents` → wait for snapshot/commit
   - `tools/call getProps` or `tools/call getHooksState` using that `fid`
3. Only **after** stating your diagnosis, backed by evidence, may you propose code changes.

---
> Source: [reillyjodonnell/react-debugger](https://github.com/reillyjodonnell/react-debugger) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
