# robertcgabriell.github.io

Blog de escritos de Robert C. Gabriell. GitHub Pages compila la web con Jekyll automáticamente al hacer push a `master`.

## Publicar un escrito nuevo

Crea un archivo en `_posts/` con el nombre `AAAA-MM-DD-titulo-del-escrito.md`:

```markdown
---
title: "Título del escrito"
date: 2026-11-26
tags: ["Tales"]          # Tales, Songs, Life, Science, Art, Programming
permalink: /es/titulo-del-escrito/
---

Aquí va el texto, en Markdown.

Para versos, termina cada línea con dos espacios  
y así se respeta el salto de línea.
```

Los nombres de los temas en español se configuran en `_config.yml` (`tag_names`).
