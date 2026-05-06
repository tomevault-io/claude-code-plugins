# security

> Read-only security — only GET requests allowed

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/security/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Security — read-only

- App is **strictly read-only**. It must NEVER modify anything in NextDNS.
- The **only allowed HTTP method is GET**. No POST, PUT, PATCH or DELETE.
- Only two NextDNS endpoints are used:
  - `GET /profiles/:id/logs`
  - `GET /profiles/:id/analytics/devices`
- API token (`NEXTDNS_API_KEY`) must **never** reach the browser.

---
> Source: [maciejaszex/ndexplorer](https://github.com/maciejaszex/ndexplorer) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-30 -->
