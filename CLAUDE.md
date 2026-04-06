# CLAUDE.md

## Que es este proyecto

Curso "Fundamentos de la Fe" para nuevos creyentes. Basado en Oden (*Cristianismo Clasico*), sintetizado en 8 lecciones con preguntas de discusion. Se visualiza como wiki en GitHub usando markdown puro.

## Estructura

```
lecciones/          # 8 lecciones (00-07), contenido + preguntas integradas
assets/img/         # Logo e imagenes
assets/audio/       # Audio de sesiones (pendiente)
assets/oden-cristianismo-clasico.pdf  # Fuente unica — citar con pagina y link directo
README.md           # Indice con tabla de lecciones, badges, links a video
tmp/                # Fuentes originales (Word) — no editar
```

## Formato de cada leccion

- Titulo, navegacion prev/next, `> [!NOTE]` con resumen
- Thumbnail de YouTube (si hay video)
- Versiculo para memorizar (lecciones con cuadernillo)
- Secciones tematicas con: versiculo ancla, versiculos de apoyo en `<details open>`, ideas centrales, errores comunes como `> [!WARNING]`
- Preguntas para grupos pequeños en `<details>` colapsable al final de cada seccion (lecciones 01-03)
- Para llevar como blockquote destacado
- Citas inspiracionales y referencia a Oden al pie

## Reglas de estilo

- **Lenguaje claro y accesible.** Esto es para gente nueva en la fe, no para seminario. Evitar jerga teologica innecesaria. Si se usa un termino tecnico (hamartia, metanoia, justificacion), siempre explicarlo en lenguaje comun.
- **No ser verboso.** Decir lo que hay que decir y parar. No rellenar con frases bonitas que no agregan nada. Las soluciones sencillas son las mejores.
- **No quemar tokens.** Antes de reescribir un archivo completo, verificar si un edit puntual resuelve el problema. Preferir cambios quirurgicos sobre rewrites masivos.
- **Markdown puro.** No Jekyll, no GitHub Pages, no tooling extra. Todo debe verse bien directo en GitHub.
- **Citas patristicas con contexto.** Cuando se cita a un padre de la iglesia, incluir quien es y cuando vivio solo si es la primera vez que aparece en la leccion. No repetir.
- **Los errores comunes van como `> [!WARNING]`** con la frase entre comillas francesas en bold, seguida de la explicacion.
- **Las preguntas de discusion** van dentro de `<details>` colapsables llamados "Preguntas para grupos pequeños" al final de cada seccion tematica.

## Convenciones

- Archivos en español sin acentos en nombres de archivo: `leccion-01.md`, no `lección-01.md`
- Videos de YouTube como thumbnail clickeable: `[![texto](https://img.youtube.com/vi/ID/hqdefault.jpg)](URL)`
- Navegacion prev/next en italica al inicio y final de cada leccion
- Separadores `---` entre secciones tematicas
