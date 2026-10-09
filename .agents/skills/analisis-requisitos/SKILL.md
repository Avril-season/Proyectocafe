---
name: analisis-requisitos
description: Guía el levantamiento y la redacción de requisitos funcionales y no funcionales del Auxiliar Cafetero, con actores, formato numerado y criterios de aceptación. Úsalo cuando el usuario pida "requisitos", "levantar requisitos", "qué debe hacer el sistema" o "historias del sistema".
---

# Análisis de Requisitos — Auxiliar Cafetero

Ayuda a documentar **qué debe hacer el sistema**, sin escribir código ni proponer soluciones técnicas (el código viene después).

## Proceso

### 1. Identificar actores

Pregunta o deduce quiénes interactúan con el sistema. Típicos en una cafetería:

- **Cliente** — ve el menú y hace pedidos.
- **Barista** — prepara y despacha pedidos.
- **Administrador / Cajero** — gestiona menú, precios e inventario.
- (Opcional) **Proveedor** — abastece insumos.

### 2. Requisitos funcionales (RF)

Por cada actor, preguntar "¿qué necesita hacer?" y redactar:

```
RF-01: El sistema debe <acción> <objeto> [condición].
```

- Un requisito por línea, numerados de forma correlativa (RF-01, RF-02...).
- Verificables: debe poder comprobarse con una prueba.
- En lenguaje del dominio, **sin mencionar tecnologías** (no "usar MySQL", sino "guardar los pedidos").

Ejemplo: `RF-01: El sistema debe permitir al cliente ver el menú de productos disponibles.`

### 3. Requisitos no funcionales (RNF)

Categorías sugeridas: usabilidad, rendimiento, seguridad, disponibilidad, mantenibilidad.

```
RNF-01: El sistema debe <criterio de calidad>.
```

Ejemplo: `RNF-01: El sistema debe responder la consulta del menú en menos de 2 segundos.`

### 4. Criterios de aceptación

Para los requisitos clave, escribir en formato dado/cuando/entonces:

```
Dado que el cliente está en el menú, cuando selecciona un producto, entonces se agrega al pedido.
```

### 5. Guardar

- Funcionales → `docs/01-requisitos/funcionales.md`
- No funcionales → `docs/01-requisitos/no-funcionales.md`
- Si no existen, crear los archivos con encabezado y la lista numerada.

## Reglas

- **No inventar alcance**: preguntar al usuario antes de añadir actores o funcionalidades nuevas.
- No proponer base de datos, frameworks ni código en esta fase.
- Al terminar, resumir cuántos RF/RNF quedaron documentados y qué quedó por definir.
