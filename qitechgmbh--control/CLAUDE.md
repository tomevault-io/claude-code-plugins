# control

> This is a machine control software project.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/control/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

This is a machine control software project.

## Repository structure

### Frontend

`/electron`: Frontend code for the control software built with React and Electron.

### Backend

`/server`: Implements machine setup & loop. Exposes a REST & Socket.io API for the electron frontend.
`/ethercat-hal`: Hardware abstraction layer for Beckhoff (and possibly other EtherCat) devices and protocols.
`/ethercat-hal-derive`: Macros for ethercat-hal
`/control-core`: Generic logic for the server.

### HMI Panel Operating System

`/nixos`: Custom Linux with realtime kernel & preconfigured for touchscreens.

### Other

/docs: Documentation for the project.

## Key Guidelines

1. Follow Rust & Typescript best practices and idiomatic patterns
2. Maintain existing code structure and organization
3. Write unit tests for new functionality where applicable.
4. Document public APIs and complex logic in code. Suggest changes to the `docs/` folder when appropriate

---
> Source: [qitechgmbh/control](https://github.com/qitechgmbh/control) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
