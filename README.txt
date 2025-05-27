# Proyecto Sprint 11 — Selección de regiones óptimas para apertura de pozos petrolíferos

## Descripción del Proyecto

El objetivo de este proyecto es analizar los datos de exploración geológica de tres regiones para identificar la mejor ubicación para abrir 200 nuevos pozos petroleros. El análisis incluye la preparación de datos, entrenamiento y evaluación de un modelo de regresión lineal, cálculo de beneficios potenciales y evaluación de riesgos usando la técnica de bootstrapping.

---

## Estructura del Proyecto

- `data/`: Conjuntos de datos para cada región
    - `geo_data_0.csv`
    - `geo_data_1.csv`
    - `geo_data_2.csv`
- `notebooks/`
    - `1_exploracion_datos.ipynb`
    - `2_entrenamiento_modelo.ipynb`
    - `3_calculo_beneficios_bootstrap.ipynb`
- `requirements.txt`
- `README.md`

---

## Desarrollo y pasos del proyecto

### 1. Exploración y preparación de datos
- Carga de datos
- Análisis estadístico de columnas (media, min, max, outliers)
- Revisión de datos nulos y duplicados
- Análisis de correlación entre características y variable objetivo

### 2. Entrenamiento y validación del modelo
- División de datos (train/validación: 75/25)
- Entrenamiento de modelo de regresión lineal para cada región
- Evaluación de predicciones (RMSE, promedio)
- Análisis de resultados

### 3. Cálculo de beneficios y selección de pozos
- Selección de los 200 pozos con mayor volumen estimado en cada región
- Cálculo de ganancias potenciales
- Comparación con umbral de rentabilidad

### 4. Evaluación de riesgos — Bootstrapping
- Simulación de ganancias usando bootstrapping (1000 iteraciones)
- Cálculo de beneficio promedio, intervalo de confianza y riesgo de pérdida
- Recomendación final de región

---

## Resultados clave

- **Región recomendada:** _[Completa según tu análisis]_
- **Beneficio promedio esperado:** _[Completa según tu análisis]_
- **Intervalo de confianza del 95%:** _[Completa según tu análisis]_
- **Riesgo de pérdida:** _[Completa según tu análisis]_

---

## Instrucciones para reproducir el proyecto

1. Clona el repositorio y navega al directorio del proyecto.
2. Instala los requisitos usando:
