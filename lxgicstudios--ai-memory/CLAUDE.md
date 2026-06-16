# ai-memory

> Conversation memory and context management for AI agents.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ai-memory/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AI Memory

Conversation memory and context management for AI agents.

## Quick Start

```bash
npx ai-memory init
```

## What It Does

- Sliding window memory (last N messages)
- Token-based memory (stay within limits)
- Persistent file storage
- Search conversation history

## Usage

```bash
# List conversations
npx ai-memory list

# Show conversation
npx ai-memory show conv-123

# Search
npx ai-memory search "query"

# Generate files
npx ai-memory init
```

## Part of the LXGIC Dev Toolkit

One of 110+ free developer tools from LXGIC Studios.

- GitHub: https://github.com/lxgicstudios
- Twitter: https://x.com/lxgicstudios
- Website: https://lxgicstudios.com

## License

MIT. Free forever.

---
> Source: [lxgicstudios/ai-memory](https://github.com/lxgicstudios/ai-memory) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
