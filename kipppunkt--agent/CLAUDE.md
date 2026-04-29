# agent

> At the beginning of each conversation, carefully read @README.md.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agent/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Instructions

At the beginning of each conversation, carefully read @README.md.

## Context

This is the public distribution repo for `@kipppunkt/agent`. The source code lives in another repo you don't have access to. This repo contains:

- The npm wrapper package (postinstall downloads platform binary, bin entry forwards execution)
- The README / documentation
- GitHub Releases with platform binaries (uploaded from the other repo)

## General

- When talking with the user, be extremely concise. Sacrifice grammar for the sake of concision.
- When writing code, prefer declarative solutions over imperative ones.

## Commit guidelines

- When writing commit messages, follow these guidelines:
    - Brief commit message title that explains WHAT BEHAVIOR was changed (present tense).
    - Concise commit message body containing bullet points that explain in more detail WHAT was changed (past tense).
    - Do not include feature-codes, implementation details, or success messages.

---
> Source: [kipppunkt/agent](https://github.com/kipppunkt/agent) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-24 -->
