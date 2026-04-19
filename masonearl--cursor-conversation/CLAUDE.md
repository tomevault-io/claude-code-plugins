# cursor-conversation

> This project enables bidirectional voice conversation with Cursor IDE.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/cursor-conversation/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Cursor ElevenLabs Voice Assistant

This project enables bidirectional voice conversation with Cursor IDE.

## Architecture

- MCP server that bridges ElevenLabs STT/TTS with Cursor chat
- Real-time audio capture and playback
- Conversation loop for iterative code building

## Development Notes

- Use ElevenLabs API for both STT and TTS
- Implement Web Audio API for browser-based audio capture
- Consider using native audio libraries for desktop app
- Focus on low-latency streaming for responsive conversations

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/masonearl) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-10 -->
