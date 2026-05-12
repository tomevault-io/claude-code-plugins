# pixi-skills

> Lockfiles must be consistent with package metadata. After any change to `pixi.toml`, run `pixi lock`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pixi-skills/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

Lockfiles must be consistent with package metadata. After any change to `pixi.toml`, run `pixi lock`.

Everything runs in a pixi environment. Any command (like `pytest`) must be prefixed with `pixi run` (e.g. `pixi run pytest`).

Code formatting must align with our standards. Run `pixi run lint` before `git commit`s to ensure this.

---
> Source: [pavelzw/pixi-skills](https://github.com/pavelzw/pixi-skills) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-09 -->
