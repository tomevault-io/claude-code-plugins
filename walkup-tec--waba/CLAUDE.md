# ucp-n8n

> Boas práticas para N8n (webhooks, workflows e credenciais)

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ucp-n8n/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# N8n UCP

Ao projetar/ajustar `workflows`, `webhooks` e integração com N8n, aplique:

- Webhooks: valide assinatura quando existir, responda rapidamente (ex.: `202`) e processe pesado em fila/worker quando aplicável.
- Idempotência: dedupe eventos (ex.: por `event_id`) para evitar processamento duplicado quando o provedor reenviar.
- Credenciais: use mecanismos nativos do N8n (variáveis/credentials) e nunca logue segredos.
- Robustez: trate falhas com retry/backs off controlados e mensagens de erro seguras.
- Observabilidade: inclua `correlationId`/trace quando possível para rastrear do gatilho ao resultado.
- Escalabilidade: use modos de execução/filas adequados para picos e evite fan-out excessivo.

---
> Source: [walkup-tec/waba](https://github.com/walkup-tec/waba) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-30 -->
