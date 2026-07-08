# qedl-rs

> **qedl-rs** is a pure Rust implementation of the Qualcomm EDL (Emergency Download) toolchain.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/qedl-rs/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## Overview

**qedl-rs** is a pure Rust implementation of the Qualcomm EDL (Emergency Download) toolchain.

## Workspace Layout

| Crate | Responsibility |
|-------|----------------|
| qedl-core | Core types, errors, events |
| qedl-transport | USB/Serial transport |
| qedl-sahara | Sahara protocol |
| qedl-firehose | Firehose protocol |
| qedl-storage | GPT and partition handling |
| qedl-image | rawprogram, patch and sparse images |
| qedl-job | Job execution |
| qedl | SDK facade |
| qedl-cli | Command-line interface |

## Architecture

...

## Development Guidelines

### Code Style

...

## Core Traits

- `Job` — Device operations
- `Transport` — Communication backend
- `EventSink` — Event reporting

## Features

...

## Extending the Project

...

## Project Conventions

- Keep crates focused on a single responsibility.
- Expose public APIs through `qedl`.
- Do not access protocol crates directly from the CLI.
- Route all device I/O through `Transport`.
- Add tests for new functionality whenever possible.

## Further Reading

- `README.md`
- `docs/architecture.md`
- Crate-level documentation

---
> Source: [baiyao105/qedl-rs](https://github.com/baiyao105/qedl-rs) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-08 -->
