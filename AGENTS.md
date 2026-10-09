# Reglas del proyecto — Auxiliar Cafetero ☕

Este archivo define las reglas que deben seguir los agentes de IA (OpenCode y otros asistentes) al trabajar en este repositorio.

> Nota: el archivo se llama `AGENTS.md` porque es el nombre estándar que buscan los agentes. En Windows (sin distinción de mayúsculas) es el mismo archivo que `agents.md`.

## 1. Idioma

- Todo el trabajo, la documentación y las respuestas se hacen en **español**.

## 2. Fase actual del proyecto

- Estamos en la fase de **análisis y modelamiento** (materia: Análisis y Modelamiento de Software).
- **No escribir código** (Java, Python, JavaScript, SQL, etc.) a menos que el usuario lo pida explícitamente.
- Si una tarea implica código, primero explicar el modelo o requerimiento y **preguntar antes de avanzar**.

## 3. Organización de la documentación

- La documentación vive en `docs/`, organizada por fases numeradas:
  - `01-requisitos/` — requisitos funcionales y no funcionales.
  - `02-modelado/` — diagramas UML en Mermaid (`diagramas-secuencia/` para secuencias).
  - `03-diseno/` — decisiones de diseño.
  - `04-informes/` — informes y evidencias de la materia.
- Nombres de archivos: minúsculas, con guiones, en español (ej. `diagrama-clases.md`).
- Un diagrama por archivo, en **Mermaid** dentro de Markdown.

## 4. Skills del proyecto

Usar los skills de `.agents/skills/` cuando apliquen:

- `analisis-requisitos` — levantar y redactar requisitos.
- `modelado-uml` — crear diagramas UML.
- `revision-entregable` — revisar un entregable antes de entregarlo.

No modificar ni eliminar skills sin autorización del usuario.

## 5. Modo aprendizaje

- El usuario está aprendiendo: explicar brevemente el **porqué** de cada decisión, no solo el qué.
- Ante ambigüedad o posibles cambios de alcance, **preguntar** antes de asumir.
- No agregar alcance nuevo sin consultarlo.

## 6. Git

- Mensajes de commit en español, imperativo y concisos: `docs: agregar requisitos funcionales`.
- No commitear archivos temporales, credenciales ni datos personales.
