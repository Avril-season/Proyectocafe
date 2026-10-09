# Auxiliar Cafetero ☕

Proyecto académico de la materia **Análisis y Modelamiento de Software**.

**Auxiliar Cafetero** es un sistema de apoyo para la operación de una cafetería: gestión del menú, pedidos, inventario y atención al cliente.

> **Fase actual:** análisis y modelamiento. Aún **no hay código**.

## Estructura del proyecto

```
ProyectoCafe/
├── AGENTS.md                        Reglas para agentes de IA
├── README.md                        Este archivo
├── docs/
│   ├── 01-requisitos/               Requisitos funcionales y no funcionales
│   ├── 02-modelado/                 Diagramas UML (Mermaid)
│   │   └── diagramas-secuencia/     Diagramas de secuencia
│   ├── 03-diseno/                   Decisiones de diseño
│   └── 04-informes/                 Informes y evidencias de la materia
├── src/                             Código (vacío hasta la fase de implementación)
└── .agents/
    └── skills/                      Skills del proyecto
        ├── analisis-requisitos/     Levantar y redactar requisitos
        ├── modelado-uml/            Diagramas UML
        └── revision-entregable/     Revisión antes de entregar
```

## Skills del proyecto

| Skill | Cuándo usarlo |
| --- | --- |
| `analisis-requisitos` | Cuando quieras levantar o redactar requisitos ("qué debe hacer el sistema"). |
| `modelado-uml` | Cuando pidas diagramas UML: casos de uso, clases, secuencia, actividad, estados. |
| `revision-entregable` | Antes de entregar, para revisar completitud, coherencia y notación. |

**Cómo invocarlos:** pide la tarea en lenguaje natural (ej. "ayúdame con los requisitos del menú") o menciona el skill por su nombre (ej. "usa el skill modelado-uml para un diagrama de clases"). El agente elige el skill según su descripción.

## Roadmap

- [ ] Fase 1 — Requisitos (funcionales y no funcionales)
- [ ] Fase 2 — Modelado UML (casos de uso, clases, secuencia, actividad)
- [ ] Fase 3 — Diseño
- [ ] Fase 4 — Implementación (futura)

## Notas

- Las reglas para los agentes de IA están en [AGENTS.md](AGENTS.md).
- Los diagramas se escriben en **Mermaid** dentro de archivos Markdown para facilitar la revisión y el renderizado.
