# backend-error-codes

> Backend API error code conventions in ErrorCodes.go

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/backend-error-codes/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Backend API Errors

- Error codes and messages returned in HTTP responses must be constants in `exception/ErrorCodes.go`.
- **Legacy errors:** numeric string codes (`"9"`, `"22"`) with a paired `*Msg`; blank line between pairs.
- **AI Chat errors:** `APIHUB-AI-*` codes with the same pairing rules.
- **Variant messages** (same code, different text): declare only `*Msg` next to the parent code block — reuse the parent `Code` at call sites (see `InvalidParameterValue` + `InvalidLimitMsg`, or `AiChatValidationFailed` + `AiChatMessageTooLongMsg`). Do not add orphan `*Msg` constants without documenting which code they belong to.
- Do not use inline `Message:` strings for client-facing errors in new code.

---
> Source: [Netcracker/qubership-apihub-backend](https://github.com/Netcracker/qubership-apihub-backend) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-05 -->
