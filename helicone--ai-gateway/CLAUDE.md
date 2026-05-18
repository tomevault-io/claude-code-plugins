# project-overview

> This project is a Rust-based LLM (Large Language Model) proxy/router service that handles API requests to various LLM providers like OpenAI and Anthropic.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/project-overview/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# LLM Proxy Project Overview

This project is a Rust-based LLM (Large Language Model) proxy/router service that handles API requests to various LLM providers like OpenAI and Anthropic.

## Key Files and Directories

- [ai-gateway/src/main.rs](mdc:ai-gateway/src/main.rs) - Main entry point for the application
- [ai-gateway/src/lib.rs](mdc:ai-gateway/src/lib.rs) - Exposes the main modules of the application
- [ai-gateway/src/app.rs](mdc:ai-gateway/src/app.rs) - Core application setup and HTTP server
- [ai-gateway/src/router/](mdc:ai-gateway/src/router) - Contains routing logic for API requests
- [ai-gateway/src/config/](mdc:ai-gateway/src/config) - Configuration handling
- [crates/](mdc:crates) - Contains smaller crates for specific functionality

## Specialized Crates

- [crates/telemetry/](mdc:crates/telemetry) - Telemetry and logging infrastructure
- [crates/metrics/](mdc:crates/metrics) - Metrics collection and reporting
- [crates/weighted-balance/](mdc:crates/weighted-balance) - Load balancing logic for LLM providers

---
> Source: [Helicone/ai-gateway](https://github.com/Helicone/ai-gateway) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-17 -->
