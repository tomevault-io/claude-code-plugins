# prompter

> prompter project conventions — agent-native Elgato Prompter CLI

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/prompter/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# prompter

This repo is **prompter**: a thin Python CLI over Camera Hub’s Prompter library (vendored PrompterKit).

## Skills

- Ops: [.cursor/skills/prompter/SKILL.md](../skills/prompter/SKILL.md)
- Dev: [.cursor/skills/prompter-dev/SKILL.md](../skills/prompter-dev/SKILL.md)

## Defaults

- Live writes use `--restart`
- No user script bodies or device serials in commits
- Keep PrompterKit vendor + THIRD_PARTY license in sync
- Update README + skills when UX changes

---
> Source: [bcharleson/prompter](https://github.com/bcharleson/prompter) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-02 -->
