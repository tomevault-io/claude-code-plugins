# agentic-expense-manager

> This file provides guidance to AI Agents when working with code in this repository.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agentic-expense-manager/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

This file provides guidance to AI Agents when working with code in this repository.

## Project Overview
Expense Manager is a web application to manage personal financial information.

## Build Commands

### Maven Commands
- **Full build with tests**: `./mvnw clean verify`
- **Run application**: `./mvnw spring-boot:run`
- **Code formatting**: `./mvnw spotless:apply`
- **Docker image build**: `./mvnw -Prelease clean compile spring-boot:build-image -DskipTests`

### Task Commands (using Taskfile)
- **Default (test)**: `task`
- **Run tests**: `task test`
- **Format code**: `task format`
- **Build Docker image**: `task build_image`
- **Start application**: `task start`
- **Stop application**: `task stop`

### Test Commands
- **Unit tests only**: `./mvnw test`
- **Integration tests only**: `./mvnw failsafe:integration-test`
- **Single test class**: `./mvnw test -Dtest=ClassName`
- **Test with coverage**: `./mvnw clean verify` (includes JaCoCo coverage with 70% minimum)

---
> Source: [sivaprasadreddy/agentic-expense-manager](https://github.com/sivaprasadreddy/agentic-expense-manager) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-06 -->
