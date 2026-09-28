# yii2-assets-auto-compress

> Перед изменением CSS-компиляции прочитать

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/yii2-assets-auto-compress/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Разработка пакета

Перед изменением CSS-компиляции прочитать
[документ о локальной копии mrclay CSS](src/vendor/mrclay/README.md).
Сохранять лицензию, происхождение и совместимость результата. Не возвращать
обязательную зависимость mrclay/minify ради CSS и не добавлять LESS-компилятор.
Переход на другой CSS-движок — отдельная задача с проверкой совместимости.

После изменений запускать PHP lint и tests/css-compatibility.php; HTML-изменения
проверять также tests/html-compressor.php. В composer.lock потребителей ничего
не менять механическим удалением записей: зависимости обновляет Composer.

---
> Source: [skeeks-semenov/yii2-assets-auto-compress](https://github.com/skeeks-semenov/yii2-assets-auto-compress) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-27 -->
