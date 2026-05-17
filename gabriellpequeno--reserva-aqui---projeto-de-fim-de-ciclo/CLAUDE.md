# engineering-security

> Lembretes de seguranca ao alterar codigo ou configuracao.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/engineering-security/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Engineering — Security

- Autenticacao e autorizacao devem ser explicitas em cada recurso sensivel.
- Nunca commitar segredos; usar variaveis de ambiente e gestao segura de credenciais.
- Tratar toda entrada externa como nao confiavel (SQL, comando, path, SSRF).
- Dependencias: preferir verificacao (`npm audit`, ferramentas do projeto) antes de releases.
- Em duvida entre falhar aberto ou fechado, preferir falha segura (deny).

---
> Source: [gabriellpequeno/Reserva-Aqui---Projeto-de-fim-de-ciclo](https://github.com/gabriellpequeno/Reserva-Aqui---Projeto-de-fim-de-ciclo) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-17 -->
