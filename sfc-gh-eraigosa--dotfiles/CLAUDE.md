# dotfiles

> Skill for starting a persistent `claude --remote-control` session on any remote

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/dotfiles/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# ai/skills/remote-claude-session/

Skill for starting a persistent `claude --remote-control` session on any remote
SSH host inside a specified git repository, via a named tmux session that survives
disconnects.

See `SKILL.md` for the full step-by-step workflow (validate alias → detect Claude
→ check existing session → start → verify → report attach command).

**Planned integration:** `tmux-mgr remote start <alias>` — see
`docs/mbo/designs/tmux-mgr-remote-command.md` for the design.

---
> Source: [sfc-gh-eraigosa/dotfiles](https://github.com/sfc-gh-eraigosa/dotfiles) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-25 -->
