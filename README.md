# Matemáticas

Espacio de estudio de cálculo de varias variables y de probabilidad y estadística,
con Claude como tutor. Las instrucciones del tutor están en `CLAUDE.md` y el avance
en `progreso.md`.

## Estructura

```
.
├── CLAUDE.md        instrucciones y método del tutor
├── progreso.md      perfil, avance y bitácora de sesiones
├── apuntes/         resúmenes de cada tema
├── ejercicios/      ejercicios resueltos y corregidos
├── Cálculo de varias variables - Stewart_compressed.pdf
└── Probabilidad_y_Estadistica_-_Walpole_Mye.pdf
```

## Stewart — *Cálculo de varias variables* (6ª ed.)

Página del PDF = página del libro − 600.

| Cap. | Tema | Pág. libro |
|---|---|---|
| 10 | Ecuaciones paramétricas y coordenadas polares | 620 |
| 11 | Sucesiones y series infinitas | 674 |
| 12 | Vectores y la geometría del espacio | 764 |
| 13 | Funciones vectoriales | 816 |
| 14 | Derivadas parciales | 854 |
| 15 | Integrales múltiples | 950 |
| 16 | Cálculo vectorial | 1026 |
| 17 | Ecuaciones diferenciales de segundo orden | 1110 |

## Walpole, Myers, Myers y Ye — *Probabilidad y estadística para ingeniería y ciencias* (9ª ed.)

Página del PDF = página del libro + 22.

| Cap. | Tema | Pág. libro |
|---|---|---|
| 1 | Introducción a la estadística y al análisis de datos | 1 |
| 2 | Probabilidad | 35 |
| 3 | Variables aleatorias y distribuciones de probabilidad | 81 |
| 4 | Esperanza matemática | 111 |
| 5 | Algunas distribuciones de probabilidad discretas | 143 |
| 6 | Algunas distribuciones continuas de probabilidad | 171 |
| 7 | Funciones de variables aleatorias (opcional) | 211 |
| 8 | Distribuciones de muestreo fundamentales y descripciones de datos | 225 |
| 9 | Problemas de estimación de una y dos muestras | 265 |
| 10 | Pruebas de hipótesis de una y dos muestras | 319 |
| 11 | Regresión lineal simple y correlación | 389 |
| 12 | Regresión lineal múltiple y ciertos modelos no lineales | 443 |
| 13 | Experimentos con un solo factor: generales | 507 |
| 14 | Experimentos factoriales (dos o más factores) | 561 |
| 15 | Experimentos factoriales 2^k y fracciones | 597 |
| 16 | Estadística no paramétrica | 655 |
| 17 | Control estadístico de la calidad | 681 |
| 18 | Estadística bayesiana | 709 |

## Ruta sugerida

Los dos cursos se pueden llevar en paralelo; estos son los puntos donde uno
alimenta al otro:

1. **Walpole 1–2** (datos, probabilidad) y **Stewart 10–11** (paramétricas, series).
2. **Walpole 3–4** (variables aleatorias, esperanza) — usa integrales de una variable;
   las distribuciones conjuntas (3.4) piden integrales dobles → **Stewart 15.1–15.3**.
3. **Walpole 5–6** (distribuciones) junto con **Stewart 12–14** (vectores, derivadas parciales).
4. **Walpole 7–8** (cambio de variable, distribuciones muestrales) ↔ **Stewart 15.9**
   (jacobiano) y 15.4 (la integral de la normal en polares).
5. **Walpole 9–10** (estimación, pruebas de hipótesis).
6. **Walpole 11–12** (regresión) ↔ **Stewart 14.7** (mínimos cuadrados como un problema de optimización).
7. **Stewart 16–17** y **Walpole 13–18** según intereses.
