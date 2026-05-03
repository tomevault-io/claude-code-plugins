# shell

> All terminal commands must use devenv shell

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/shell/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


**MANDATORY:** Wrap ALL terminal commands with `devenv shell --`

```bash
# ✅ DO
devenv shell -- git status
devenv shell -- nix flake check
devenv shell -- cargo build

# ❌ DON'T
git status
nix flake check
cargo build
```

**Applies to:** All terminal commands (git, nix, cargo, formatting, testing, etc.)

---
> Source: [Industrial/id_effect](https://github.com/Industrial/id_effect) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-24 -->
