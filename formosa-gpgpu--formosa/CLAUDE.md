# formosa

> - Do not assume `direnv` is active in the shell. Check with `direnv status`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/formosa/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Notes

- Do not assume `direnv` is active in the shell. Check with `direnv status`
  or environment variables such as `DIRENV_DIR` / `IN_NIX_SHELL` before relying
  on the flake environment.
- Prefer running commands through `direnv exec . <command>` so they use the
  repo's `.envrc` environment.
- If `direnv exec . <command>` reports that `.envrc` is blocked, run
  `direnv allow` in the repo first.
- If `direnv` is unavailable or cannot load the environment, fall back to
  `nix develop -c <command>`.

---
> Source: [FORMOSA-GPGPU/formosa](https://github.com/FORMOSA-GPGPU/formosa) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-30 -->
