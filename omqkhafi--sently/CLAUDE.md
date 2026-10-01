# sently-first-provider-model

> Sently-first provider model — channel senders are the API; vendors are transports.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/sently-first-provider-model/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Sently-first provider model

Apps use **sently channel senders**, not vendor SDKs.

- Email → `createMailer` / `createSMTPMailer` + `Transport`
- SMS → `createSmsSender` + `SmsTransport`
- WhatsApp → `createWhatsAppSender` + `WhatsAppTransport`
- Push → `createPushSender` + `PushTransport`

**Providers are transports** under those senders. Swap the transport; app code stays on sently.

**Do not** make a mega vendor client (`new Taqnyat()`, `new Msegat()` as a full SDK) the primary surface.

**Multi-product vendors** (Taqnyat SMS / WhatsApp / mail / verify): one transport per channel (`taqnyat-sms`, `taqnyat-whatsapp`, …), each wired into the matching `create*Sender`.

**Vendor extras** (OTP send/verify, cost, templates): methods on the concrete transport only (pattern: `MsegatTransport.sendOtp` / `verifyOtp`). Never add them to the shared channel contract.

**New channels** (e.g. Voice): add a library-wide sender + types first; then provider transports.

---
> Source: [omqkhafi/sently](https://github.com/omqkhafi/sently) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-01 -->
