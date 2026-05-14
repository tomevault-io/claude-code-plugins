# auth-security

> - Use Clerk for auth; rely on middleware guards for protected areas

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/auth-security/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

- Use Clerk for auth; rely on middleware guards for protected areas
- Do not leak user/session info to the client; serialize minimal data
- Respect `X-Frame-Options: DENY` and CSP defined in `next.config.js`
- Sanitize any user-provided HTML/Markdown; use `sanitize-html` or `dompurify` on the server when possible
- Prefer server-side checks over client-side gating

---
> Source: [Saksham-Goel1107/Dionysus](https://github.com/Saksham-Goel1107/Dionysus) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-13 -->
