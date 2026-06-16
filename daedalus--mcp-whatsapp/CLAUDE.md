# mcp-whatsapp

> MCP server exposing WhatsApp bot functionality.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mcp-whatsapp/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# MCP WhatsApp

MCP server exposing WhatsApp bot functionality.

## When to use this skill

Use this skill when you need to:
- Send messages via WhatsApp
- Send media files
- Send locations

## Tools

- `send_message` - Send text message
- `send_media` - Send image/document
- `send_location` - Send location
- `connect_whatsapp` / `disconnect_whatsapp` - Connection

## Adapters

- pywhatkit (WhatsApp Web)
- whatsapp-business (WhatsApp Business API)

## Install

```bash
pip install mcp-whatsapp[pywhatkit]
# or
pip install mcp-whatsapp[whatsapp-business]
```

---
> Source: [daedalus/mcp-whatsapp](https://github.com/daedalus/mcp-whatsapp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
