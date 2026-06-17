# testing

> Testing conventions for Chat Agent Relay (CAR)

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/testing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Testing Conventions

- Use bun:test (describe, it, expect, beforeAll, afterAll)
- Test files go in tests/ directory alongside src/
- New adapters MUST pass conformance tests from @chat-agent-relay/adapter-conformance
- All canonical events must validate against JSON Schema via ContractHarnessValidators
- Mock external services with Bun.serve() on port 0 for random port assignment
- Never use real API keys in tests
- Test both success and error paths

---
> Source: [ChatAgentRelay/ChatAgentRelay](https://github.com/ChatAgentRelay/ChatAgentRelay) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-17 -->
