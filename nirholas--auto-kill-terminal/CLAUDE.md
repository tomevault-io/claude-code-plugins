# auto-kill-terminal

> - **Always use background terminals** (`isBackground: true`) for every command so a terminal ID is returned

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/auto-kill-terminal/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# auto-kill-terminal

## Terminal Management

- **Always use background terminals** (`isBackground: true`) for every command so a terminal ID is returned
- **Always kill the terminal** after the command completes, whether it succeeds or fails — never leave terminals open
- Do not reuse foreground shell sessions — stale sessions block future terminal operations in Codespaces
- In GitHub Codespaces, agent-spawned terminals may be hidden — they still work. Do not assume a terminal is broken if you cannot see it
- If a terminal appears unresponsive, kill it and create a new one rather than retrying in the same terminal

---
> Source: [nirholas/auto-kill-terminal](https://github.com/nirholas/auto-kill-terminal) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-02 -->
