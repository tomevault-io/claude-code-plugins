# oh-my-dsh-plugins

> - Plugin source is grouped by feature under `plugins/<plugin-name>/`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/oh-my-dsh-plugins/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

- Plugin source is grouped by feature under `plugins/<plugin-name>/`.
- Keep package-specific implementation, tests, and documentation inside its plugin directory.
- Generated output belongs in `plugins/*/lib/` and must remain untracked.
- Release staging belongs in root `release/` and must remain untracked.
- Run `pnpm check` from the repository root before release.
- Keep plugins installable without modifying the DeepSeek Harness source tree.
- When adding a plugin, add its package name to the GitHub Actions matrix and its directory to the root installer.

---
> Source: [weekitmo/oh-my-dsh-plugins](https://github.com/weekitmo/oh-my-dsh-plugins) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-18 -->
