# software-brain

Base de conocimiento personal sobre desarrollo de software, escrita en Markdown y pensada para abrirse como *vault* de [Obsidian](https://obsidian.md).

## Descripción

Este repositorio reúne notas, conceptos, guías y referencias del mundo del software: lenguajes, arquitectura, herramientas, buenas prácticas, DevOps, bases de datos y más. Las notas están enlazadas entre sí para formar un grafo de conocimiento navegable.

## Uso

1. Clona el repositorio:
   ```bash
   git clone <url-del-repositorio>
   ```
2. Abre Obsidian → **Open folder as vault** → selecciona la carpeta del repositorio.
3. Empieza por la nota de entrada (`00 - Inbox` o el índice principal) y navega mediante enlaces `[[wikilinks]]`.

## Estructura

El contenido se organiza en directorios temáticos en la raíz del repositorio, uno por área del software:

```
software-brain/
├── frontend/       # Interfaces, frameworks web, UX, accesibilidad...
├── backend/        # APIs, servicios, lógica de negocio, autenticación...
├── arquitectura/   # Patrones, diseño de sistemas, decisiones técnicas...
├── ...             # Nuevas áreas (devops, datos, testing, seguridad...)
├── templates/      # Plantillas de notas
└── attachments/    # Imágenes y ficheros adjuntos
```

- Cada área es un directorio en la raíz; se crean nuevas conforme el contenido lo requiera.
- Dentro de cada área se pueden añadir subdirectorios por tecnología o subtema (por ejemplo, `frontend/react/`).
- `templates/` y `attachments/` son transversales y no pertenecen a ninguna área.

> La lista de áreas es abierta y evolucionará con el contenido.

## Convenciones

- **Nombres de fichero:** claros y descriptivos, en minúsculas y con guiones (`patron-observer.md`).
- **Idioma:** español, manteniendo los términos técnicos en inglés cuando sean el estándar.
- **Enlaces:** usar `[[wikilinks]]` para relacionar notas.
- **Etiquetas:** `#tema/subtema` para clasificar (por ejemplo, `#lenguaje/python`).
- **Frontmatter:** cada nota puede incluir metadatos YAML:
  ```yaml
  ---
  title: Título de la nota
  tags: [tema, subtema]
  created: 2026-01-01
  updated: 2026-01-01
  ---
  ```
- **Adjuntos:** guardar en `attachments/` y enlazar desde la nota.

## Plugins recomendados

Opcionales; el vault funciona sin ellos.

- Templater
- Dataview
- Calendar

## Contribuir

Es un repositorio personal, pero las sugerencias son bienvenidas mediante *issues* o *pull requests*.

## Licencia

Por definir.
