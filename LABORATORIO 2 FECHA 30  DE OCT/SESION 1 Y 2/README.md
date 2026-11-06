# Laboratorio 2 — El índice sancocho

Cálculo Diferencial — Universidad Nacional de Colombia, Sede Manizales

- **Sesión 1:** 30 de octubre de 2026 — *La receta como función* (pipeline de funciones puras y `componer()`)
- **Sesión 2:** *El índice en el tiempo y el duelo de ciudades* (índice 2013–2024, picos, conmutatividad, unidad sancocho y plato propio)

**Cuadernos en Google Colab:**
- Sesión 1: [abrir en Colab](https://colab.research.google.com/drive/1yBDFuvTcBGRz35FnihQYGZIaXxDanc_l)
- Sesión 2: [abrir en Colab](https://colab.research.google.com/drive/13wzAA6N39vDe9ErFV6YkXrMiO5khh6St)

## Integrantes

- Thomas Ramírez Villa
- Sebastián Gutiérrez Rodríguez
- Nicol Velez Arboleda
- Sofía Hoyos Tabares

## Contenido

| Carpeta | Qué hay |
|---|---|
| `BITACORAS/` | Bitácoras individuales de uso de IA, con la cacería estrella |
| `CODIGO SESION 1/` | Cuaderno de la sesión 1 (auditoría de dominios, nombres oficiales, `RECETA`, funciones puras, `componer()`, P1–P3) |
| `CODIGO SESION 2/` | Cuaderno de la sesión 2 (índice de Manizales, picos, duelo de ciudades, conmutatividad, unidad sancocho, plato propio y Momento 3) |
| `TAREA PUENTE/` | Verificación del congelado SIPSA y defensa del precio medio |
| `FOTOS ( EVIDENCIA )/` | Predicciones a mano del Momento 1: P1–P3 (sesión 1) y P4–P5 (sesión 2) |
| `FOTOS ( TAREA PUENTE )/` | Pantallazo de la verificación del congelado |

## Resultados principales

- **Índice sancocho, Manizales:** \$13.695 (2013-01) → \$28.634 (2024-12), **+109,1 %**.
- **Duelo de ciudades (2024-12):** Bogotá \$40.740 · Manizales \$28.634 · Medellín \$24.792.
- **Conmutatividad (2016):** con el promedio, los dos caminos dan \$15.587,53; con la mediana difieren en \$63,05. La receta es lineal y la mediana no.
- **Plato propio:** frijolada, \$12.140 → \$28.015 (**+130,8 %**).

**Nota sobre la tarea puente:** el portal de microdatos del DANE respondió `HTTP 401: Unauthorized` al script `congelar_sipsa.py`, así que los controles del README del curso se verificaron sobre el congelado del curso y no con una reproducción desde la fuente. Está explicado en el cuaderno.

**Pendiente:** bitácora de IA y cacería estrella de Sofía.

## Datos

- Precios mayoristas: SIPSA-P del DANE (conjunto `gkqq-k3k5`), congelado del curso `sipsa_mensual.csv.gz` (666.865 filas, 2013-01 a 2024-12, 71 ciudades, 385 productos).
- Salario mínimo: Decreto 2738 de 2012 (2013) y Decreto 2292 de 2023 (2024).
