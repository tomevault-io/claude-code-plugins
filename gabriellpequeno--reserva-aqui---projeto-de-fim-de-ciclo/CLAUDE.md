# engineering-backend

> Convencoes para APIs e codigo de servidor.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/engineering-backend/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Engineering — Backend

- Valide entrada na borda (schema/types); nao confie no cliente.
- Separe rota/handler, regra de negocio e acesso a dados quando fizer sentido.
- Erros: status HTTP corretos; nao vazar detalhes internos em producao.
- Pense em idempotencia, timeouts e limites de taxa para endpoints expostos.
- Evite I/O sincrono bloqueante no caminho quente do request.

---
> Source: [gabriellpequeno/Reserva-Aqui---Projeto-de-fim-de-ciclo](https://github.com/gabriellpequeno/Reserva-Aqui---Projeto-de-fim-de-ciclo) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-17 -->
