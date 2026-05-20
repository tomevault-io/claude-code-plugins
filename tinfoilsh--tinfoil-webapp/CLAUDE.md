# tinfoil-webapp

> Never use console.log/error/warn in production code. Use the logging utilities from `@/utils/error-handling`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tinfoil-webapp/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Logging in this project

Never use console.log/error/warn in production code. Use the logging utilities from `@/utils/error-handling`.

# Building and Running

NEVER run npm run dev, npm start, or start the development server. Only make code changes and let the user handle running the server and build commands.

# API Requests

NEVER use raw fetch() for API requests to Tinfoil enclaves. Always use the TinfoilAI SDK client (via getTinfoilClient or getWebSearchClient). The SDK handles attestation verification which is critical for security.

---
> Source: [tinfoilsh/tinfoil-webapp](https://github.com/tinfoilsh/tinfoil-webapp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
