# zzusage

> Zig 0.15 reimplementation of ccusage (Claude Code usage analyzer).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/zzusage/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# zzusage Agent Notes

Zig 0.15 reimplementation of ccusage (Claude Code usage analyzer).

## Build

```bash
zig build        # compile
zig build run    # run
zig build test   # test
```

## Key References

- [Zig 0.15 I/O API](docs/zig-0.15-io-api.md) - stdout, writers, ArrayList changes
- libvaxis dependency for TUI mode

## Architecture

- `src/main.zig` - single-file implementation
- JSONL parsing from `~/.config/claude/projects/` and `~/.claude/projects/`
- Commands: daily, weekly, monthly, sessions, blocks, statusline

---
> Source: [joelreymont/zzusage](https://github.com/joelreymont/zzusage) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-26 -->
