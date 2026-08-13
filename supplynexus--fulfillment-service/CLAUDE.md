# api-security

> 编辑前后端 API 鉴权/加密时参考——签名顺序、头、加解密

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/api-security/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# API 安全（按需参考）

- **鉴权**：前后端用租户密钥签名。签名字符串顺序：`{METHOD}{PATH}{timestamp}{nonce}{tenantName}{body}`；头：`X-Tenant-Name`, `X-Timestamp`, `X-Nonce`, `X-Signature`, `X-User-ID`。时间戳 Unix 秒，GET body 空串。实现见 `@/lib/key-loader`、`@/lib/signature` 的 `generateBackendSignature`。
- **加解密**：敏感凭据加解密存储与传输（`encrypt_data`/`decrypt_data`）；使用前解密，日志不记敏感数据。
- **ID**：见 api-id-hashid.mdc；返回用 `id_hashid`，不暴露数字主键。

---
> Source: [supplynexus/fulfillment-service](https://github.com/supplynexus/fulfillment-service) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-13 -->
