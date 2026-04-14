# bookpollmanager

> This project is a Discord bot for managing book club polls, running as a Cloudflare Worker. It's built with JavaScript, uses vitest for testing, and is configured with wrangler.toml.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/bookpollmanager/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

This project is a Discord bot for managing book club polls, running as a Cloudflare Worker. It's built with JavaScript, uses vitest for testing, and is configured with wrangler.toml.


Key features include:
  - Creating and managing polls.
  - Two voting systems: "Chris-style" (top-three, points-based) and ranked-choice.
  - Interaction via Discord slash commands and message components.
  - Data persistence for polls, nominations, and votes through a pollManager.


The code is structured with distinct directories for commands, interactions, utilities, services, and database schema.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/morgangrubb)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/morgangrubb)
<!-- tomevault:4.0:claude_md:2026-04-09 -->
