# TomeVault Claude Code plugins

Instruction files in `CLAUDE.md` format, published as a Claude Code plugin marketplace by [TomeVault](https://tomevault.io).

Every plugin here was indexed from a public GitHub repository, scanned for credential leaks, prompt injection, and unsafe shell patterns, and graded before publication. The same files are converted and published in parallel for Codex, GitHub Copilot, Cursor, the Gemini CLI, and Windsurf, so behaviour authored for one agent runs on all of them.

## Install

Add this repository as a custom marketplace in `.claude/settings.json`:

```json
{
  "pluginMarketplaces": ["https://github.com/tomevault-io/claude-code-plugins"]
}
```

Then browse and install individual plugins from the registry.

## Browse

Search, filter, and check the scan grade for any file at [tomevault.io](https://tomevault.io).

---

Indexed, verified, and distributed by TomeVault.
