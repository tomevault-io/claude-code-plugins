# fd-leak

> In this file sandbox-api/src/handler/process/process.go

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/fd-leak/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


In this file sandbox-api/src/handler/process/process.go
type ProcessInfo should never make a link to exec.Cmd cause this can cause FD leak
You should always use ProcessPid for link to CMD

---
> Source: [blaxel-ai/sandbox](https://github.com/blaxel-ai/sandbox) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
