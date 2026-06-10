# epubtrans

> - EPUB translation using LLMs (Large Language Models)

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/epubtrans/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Overview

## Core Functionalities

- EPUB translation using LLMs (Large Language Models)
- Support for multiple LLM providers (Anthropic, DeepSeek)
- Batch processing with rate limiting
- Concurrent translation processing
- HTML content preservation
- CLI interface with robust error handling

## Tech Stack

- Go (Primary language)
- LLM APIs (Anthropic Claude, DeepSeek)
- Cobra (CLI framework)
- goquery (HTML processing)

## Error Handling

- Use custom error types for specific scenarios
- Implement proper error wrapping
- Handle rate limits and API failures gracefully
- Implement retry mechanisms with exponential backoff

## Performance Considerations

- Batch processing for optimal API usage
- Concurrent processing with proper synchronization
- Memory-efficient content handling
- Rate limiting to prevent API throttling

---
> Source: [nguyenvanduocit/epubtrans](https://github.com/nguyenvanduocit/epubtrans) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-10 -->
