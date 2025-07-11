# 🍷 Clasificación de Calidad de Vino - Machine Learning

Este proyecto aplica técnicas de clasificación para predecir la calidad del vino tinto utilizando variables físico-químicas. A través del análisis exploratorio, preprocesamiento, entrenamiento y evaluación de modelos, buscamos identificar qué características influyen en la percepción de calidad.

---

## 🎯 Objetivo

Utilizar técnicas de clasificación aprendidas hasta el momento para predecir la **calidad del vino** basándose en sus propiedades físico-químicas. Esto permite aplicar:

- Selección de características
- Preprocesamiento de datos
- Entrenamiento y evaluación de modelos
- Interpretación de métricas
- Visualización de resultados

---

## 📂 Dataset

**Wine Quality Dataset**  
Disponible en [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)

### 🔬 Descripción

Contiene observaciones de vino tinto con variables como:

- Acidez fija, acidez volátil, ácido cítrico
- Azúcar residual, cloruros, SO₂ libre y total
- Densidad, pH, sulfatos, alcohol
- **Quality**: variable objetivo en una escala de 0 a 10

---

## 🧪 Instrucciones de desarrollo

### 1️⃣ Carga y Exploración de Datos

- Importar y revisar la estructura del dataset
- Analizar distribuciones y relaciones entre variables
- Tratar valores nulos y detectar outliers

### 2️⃣ Preprocesamiento de Datos

- Seleccionar variables predictoras más relevantes
- Transformar categóricas en numéricas si aplica
- Dividir en conjunto de entrenamiento y prueba
- Escalar las variables numéricas

### 3️⃣ Entrenamiento de Modelos

Se entrenaron 3 modelos de clasificación:

- `Regresión Logística`
- `K-Nearest Neighbors (KNN)`
- `Random Forest Classifier`

### 4️⃣ Comparación y Análisis

- **KNN mostró el menor error promedio (MSE = 0.3789)** → predicciones más precisas
- **KNN también logró el mayor R² (0.3753)** → mejor capacidad explicativa
- **Random Forest** tuvo desempeño intermedio pero es más robusto ante ruido y no linealidades
- **Regresión Lineal** fue clara y rápida pero limitada en precisión

#### 🔍 Fortalezas por modelo

| Modelo               | Fortalezas                          | Debilidades                              |
|----------------------|-------------------------------------|------------------------------------------|
| Regresión Lineal     | Muy interpretable, rápida           | No capta relaciones complejas            |
| KNN Regressor        | Flexible, buen rendimiento          | Sensible al ruido y escalado             |
| Random Forest Class. | Robusto, excelente para clasificación | Menos interpretable, más costoso         |

---

## 🗃️ Repositorio y Liberación

- Código y análisis disponibles en este repositorio
- Incluye notebooks, visualizaciones, y documentación
- Tag de liberación: `v1.0` — primera versión estable con resultados completos

---



