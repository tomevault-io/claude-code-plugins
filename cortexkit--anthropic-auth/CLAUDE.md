# anthropic-auth

> The `captures/` directory is for local system-prompt captures from Claude Code and OpenCode via mitmproxy HTTPS interception. Capture artifacts are ignored by git; use them locally to verify proxy transform accuracy and understand what each tool sends to the Anthropic API.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/anthropic-auth/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Notes

## Captured system prompts

The `captures/` directory is for local system-prompt captures from Claude Code and OpenCode via mitmproxy HTTPS interception. Capture artifacts are ignored by git; use them locally to verify proxy transform accuracy and understand what each tool sends to the Anthropic API.

- **Capture traffic**: `./scripts/capture-with-mitmproxy.sh -o <name>.flow -- <command>`
- **Extract prompt**: `bun run extract <name>.flow -o captures/<tool>-v<version>.txt`

See [captures/AGENTS.md](captures/AGENTS.md) for prerequisites, full workflow, and PII redaction rules.

---
> Source: [cortexkit/anthropic-auth](https://github.com/cortexkit/anthropic-auth) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-15 -->
