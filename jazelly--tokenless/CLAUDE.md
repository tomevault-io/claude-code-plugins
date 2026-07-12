# tokenless

> Tokenless is a standalone project. Keep it independent from Noop: Noop may consume Tokenless packages, but Tokenless must not import Noop internals or depend on Noop workspace scripts.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tokenless/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Tokenless

Tokenless is a standalone project. Keep it independent from Noop: Noop may consume Tokenless packages, but Tokenless must not import Noop internals or depend on Noop workspace scripts.

Project content, package names, docs, and code are written in English.

Use focused integration or browser-extension E2E tests for behavior that crosses the extension, runner, local runtime, or provider web sessions. Do not mock visible-session behavior when a browser proof is feasible.

Do not store or extract provider cookies, localStorage/sessionStorage tokens, hidden auth headers, or private provider backend API calls. Tokenless visible-session adapters operate only through user-visible browser UI after the user grants extension host permission.

---
> Source: [jazelly/tokenless](https://github.com/jazelly/tokenless) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-12 -->
