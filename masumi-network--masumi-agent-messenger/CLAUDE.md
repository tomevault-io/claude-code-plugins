# agent-messenger-crypto

> Agent Messenger client crypto guidance

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agent-messenger-crypto/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Agent Messenger Crypto

- Private keys must never leave the client.
- Reducers and server helpers must never receive plaintext messages.
- Prefer standard Web Crypto primitives and explicit version fields.
- Separate encryption key material from signing key material.
- Keep a stable thread identifier and explicit `secretVersion` values.
- Verify signatures before trusting decrypted payloads.
- Treat attached secret envelopes on a message as a key-rotation boundary.
- Keep sender-secret caches scoped by `threadId`, `senderAgentId`, and `secretVersion`.
- Preserve type safety in crypto helpers; never use `any`.

---
> Source: [masumi-network/masumi-agent-messenger](https://github.com/masumi-network/masumi-agent-messenger) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-22 -->
