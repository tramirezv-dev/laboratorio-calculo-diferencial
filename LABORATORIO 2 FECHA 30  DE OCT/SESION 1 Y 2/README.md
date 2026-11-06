# Laboratorio 2, el índice sancocho

Cálculo Diferencial. Universidad Nacional de Colombia, Sede Manizales.

- Sesión 1, 30 de octubre de 2026: la receta como función (pipeline de funciones puras y `componer()`).
- Sesión 2: el índice en el tiempo y el duelo de ciudades (índice 2013 a 2024, picos, conmutatividad, unidad sancocho y plato propio).

Cuadernos en Google Colab:
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
| `CODIGO SESION 1/` | Cuaderno de la sesión 1: auditoría de dominios, nombres oficiales, `RECETA`, funciones puras, `componer()`, P1 a P3 |
| `CODIGO SESION 2/` | Cuaderno de la sesión 2: índice de Manizales, picos, duelo de ciudades, conmutatividad, unidad sancocho, plato propio y Momento 3 |
| `TAREA PUENTE/` | Verificación del congelado SIPSA y defensa del precio medio |
| `FOTOS ( EVIDENCIA )/` | Predicciones a mano del Momento 1: P1 a P3 (sesión 1) y P4 y P5 (sesión 2) |
| `FOTOS ( TAREA PUENTE )/` | Pantallazo de la verificación del congelado |

## Resultados

El sancocho de Manizales pasó de \$13.695 en enero de 2013 a \$28.634 en diciembre de 2024, un 109,1 % más. En el último mes cuesta \$40.740 en Bogotá y \$24.792 en Medellín.

Para 2016, promediar y luego costear da lo mismo que costear y luego promediar: \$15.587,53 por los dos caminos. Con la mediana se separan \$63,05, porque la receta es lineal y la mediana no.

El plato propio es una frijolada. Subió de \$12.140 a \$28.015, un 130,8 %. El frijol y el tocino suman cerca del 80 % de su costo, y los saltos de 2015 y 2022 los dio el frijol.

La tarea puente no se pudo reproducir desde la fuente: el portal de microdatos del DANE respondió `HTTP 401: Unauthorized` a `congelar_sipsa.py`. Los controles del README del curso se revisaron sobre el congelado del curso y coinciden los seis. El cuaderno lo explica.

## Datos

- Precios mayoristas: SIPSA-P del DANE (conjunto `gkqq-k3k5`), congelado del curso `sipsa_mensual.csv.gz` (666.865 filas, 2013-01 a 2024-12, 71 ciudades, 385 productos).
- Salario mínimo: Decreto 2738 de 2012 (2013) y Decreto 2292 de 2023 (2024).
