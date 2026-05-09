# sdk-validation

> Caido SDK API Validation

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/sdk-validation/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Caido SDK API Validation

## Valid API Usage

Always use documented Caido SDK APIs directly without runtime checks or validation.

- Good
  ```typescript
  sdk.window.showToast("Message", { variant: "error" });
  sdk.backend.myFunction();
  sdk.commands.register("my-command", { name: "Command", run: () => {} });
  ```

- Bad (NEVER do this)
  ```typescript
  if ("showToast" in sdk.window && typeof sdk.window.showToast === "function") {
    sdk.window.showToast("Message");
  }
  ```

## Rules

1. Never use runtime API existence checks (`typeof`, `in` operator)
2. Never assume undocumented SDK methods exist
3. If unsure about an API, ask for clarification rather than guessing

The SDK is typed and guaranteed to have the documented methods available.

---
> Source: [caido-community/authswap](https://github.com/caido-community/authswap) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-05 -->
