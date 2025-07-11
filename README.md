# 🍷 Clasificación de Calidad de Vino — Proyecto de Machine Learning

Este proyecto utiliza técnicas de clasificación y regresión para predecir la calidad del vino tinto a partir de características físico-químicas. Aplicamos modelos como Regresión Lineal, KNN y Random Forest, acompañados de métricas, visualizaciones y análisis comparativos.

---

## 🎯 Objetivo

Aplicar conceptos clave de machine learning para predecir la calidad del vino utilizando:

- Selección de características
- Preprocesamiento de datos
- Entrenamiento de modelos
- Evaluación con métricas de clasificación
- Análisis visual y comparativo

---

## 📂 Dataset

**Wine Quality Dataset**  
Fuente: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)

### 🔬 Descripción

Este conjunto de datos incluye variables físico-químicas de muestras de vino tinto como:

- Acidez fija, acidez volátil, ácido cítrico  
- Azúcar residual, cloruros, dióxido de azufre libre y total  
- Densidad, pH, sulfatos, alcohol  
- `quality`: variable objetivo (escala 0–10)

---

## ⚙️ Instrucciones del proyecto

### 1️⃣ Carga y Exploración de Datos

- Cargar y revisar estructura del dataset  
- Analizar distribuciones y detectar outliers  
- Tratar valores nulos si existen

### 2️⃣ Preprocesamiento

- Selección de variables predictoras  
- Escalado de características numéricas  
- División en conjuntos de entrenamiento y prueba

### 3️⃣ Entrenamiento de Modelos

- Se entrenaron tres modelos:
  - Regresión Lineal (`LinearRegression`)
  - K-Nearest Neighbors (`KNeighborsRegressor`)
  - Random Forest (`RandomForestClassifier`)

- Se aplicó validación cruzada y optimización de hiperparámetros (`GridSearchCV`)


## 4️⃣  Resultados comparativos

| Modelo                  | MSE ↓       | R² ↑        |
|--------------------------|-------------|-------------|
| Regresión Lineal         | 0.4071      | 0.3288      |
| Random Forest Classifier | **0.3186**  | **0.4746**  |
| KNN Regressor            | 0.3789      | 0.3753      |

---

### 🥇 Análisis general

- **Random Forest** logró el menor MSE y el mayor R², mostrando excelente capacidad de predicción y explicabilidad de la calidad del vino.
- **KNN** obtuvo métricas competitivas, destacando como modelo flexible y eficaz en estimaciones puntuales.
- **Regresión Lineal** fue rápida y clara, ideal como modelo base interpretativo, aunque limitada ante relaciones no lineales.

---

### 🔍 Fortalezas por modelo

| Modelo                  | Fortalezas                                   | Debilidades                                  |
|--------------------------|----------------------------------------------|----------------------------------------------|
| Regresión Lineal         | Fácil de interpretar, rápida                 | No capta relaciones complejas                |
| KNN Regressor            | Flexible, buen rendimiento local             | Sensible al escalado y ruido                 |
| Random Forest Classifier | Robusto, excelente rendimiento clasificatorio| Requiere mayor capacidad computacional       |

---
## 🗃️ Repositorio y Liberación

- Código y análisis disponibles en este repositorio
- Incluye notebooks, visualizaciones, y documentación
- Tag de liberación: `v1.0` — primera versión estable con resultados completos

---




