# backend-service-wiring

> Service.go wiring conventions for qubership-apihub-backend

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/backend-service-wiring/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Service.go Wiring

- Add new repositories, services, and controllers at the **end** of their corresponding sections in `Service.go`.
- Use `log.Fatalf` for fail-fast fatal errors during wiring/startup in `Service.go` when initialization cannot continue.

---
> Source: [Netcracker/qubership-apihub-backend](https://github.com/Netcracker/qubership-apihub-backend) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-05 -->
