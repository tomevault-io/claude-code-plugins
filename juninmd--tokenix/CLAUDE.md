# tokenix

> **tokenix** — Rust CLI for token-efficient codebase exploration. Builds a local SQLite index with in-process embeddings (fastembed/ONNX), then exposes semantic search, compact file reads, and AI-tool hook integration.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tokenix/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md — tokenix

## Project

**tokenix** — Rust CLI for token-efficient codebase exploration. Builds a local SQLite index with in-process embeddings (fastembed/ONNX), then exposes semantic search, compact file reads, and AI-tool hook integration.

Stack: Rust · SQLite · fastembed (ONNX, in-process) · Claude Code `PreToolUse` hook · background daemon (TCP)

Reduces token usage 60–90% by intercepting large reads and replacing them with focused context.

## Build & Install

---
> Source: [juninmd/tokenix](https://github.com/juninmd/tokenix) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-29 -->
