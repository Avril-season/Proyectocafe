---
name: revision-entregable
description: Revisa un entregable del proyecto (requisitos o diagramas) antes de entregarlo: completitud, coherencia entre documentos, notación UML, sintaxis Mermaid y trazabilidad con los requisitos. Úsalo cuando el usuario diga "revisa mi entrega", "revisar entregable" o "está listo para entregar".
---

# Revisión de Entregable — Auxiliar Cafetero

Revisa un entregable y **reporta hallazgos**. No corrige automáticamente: propone cambios y espera aprobación del usuario.

## Proceso

### 1. Identificar el entregable

Preguntar qué archivo o carpeta revisar (por defecto, todo `docs/`).

### 2. Checklist

- [ ] **Completitud**: los requisitos tienen actores, RF numerados, RNF y criterios de aceptación donde aplique.
- [ ] **Coherencia**: los diagramas cubren los RF y usan los mismos nombres del dominio.
- [ ] **Notación UML** correcta (multiplicidades, relaciones, actores en casos de uso).
- [ ] **Sintaxis Mermaid** válida (se puede renderizar).
- [ ] **Ubicación y nombres** de archivos según lo definido en `AGENTS.md`.
- [ ] **Sin código de implementación** (estamos en fase de análisis/modelamiento).

### 3. Reporte

Tabla de hallazgos con columnas: archivo, problema, severidad (alta / media / baja), sugerencia.

### 4. Cierre

- Si no hay hallazgos de severidad alta: indicar "listo para entregar".
- Si los hay: listar los pendientes y preguntar si el usuario quiere que se apliquen las correcciones sugeridas.
