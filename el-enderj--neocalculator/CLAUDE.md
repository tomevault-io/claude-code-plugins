# neocalculator

> - **Hardware**: ESP32 DevKit V1, TFT 3.2" (ILI9341), Matriz 6x8.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/neocalculator/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Reglas del Proyecto: Calculadora Graficadora ESP32

- **Hardware**: ESP32 DevKit V1, TFT 3.2" (ILI9341), Matriz 6x8.
- **Prioridad**: Código eficiente para microcontroladores (evitar uso excesivo de `std::string` si es posible, preferir `char*` o `String` de Arduino optimizado).
- **Parser**: Debe soportar multiplicación implícita (ej. 2x, (a)(b)) y errores detallados.
- **UI**: Orientación vertical. Estilo visual inspirado en Casio (Científica) y TI-84 (Gráficos).
- **Documentación**: Cada módulo debe tener su explicación en archivos .md en la carpeta /docs.
- **Calidad**: Antes de dar por finalizado un módulo matemático, genera tests unitarios básicos para verificar resultados.

---
> Source: [El-EnderJ/NeoCalculator](https://github.com/El-EnderJ/NeoCalculator) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-21 -->
