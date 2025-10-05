# Trabajo Práctico N°1 – Minería de Datos

## Descripción
Este proyecto corresponde al **Trabajo Práctico N°1** de la materia *Minería de Datos (2025)*.  
El objetivo principal es aplicar los conocimientos adquiridos en las unidades 2 y 3 sobre análisis exploratorio, reducción de dimensionalidad y técnicas de clustering, utilizando un conjunto de datos reales sobre cultivos.

El trabajo incluye todas las etapas del proceso de minería de datos: desde la exploración y limpieza del dataset hasta la aplicación e interpretación de diferentes algoritmos.

---

## Objetivos
- Realizar un **análisis exploratorio de datos (EDA)**.  
- Aplicar **PCA**, **Isomap** y **t-SNE** para reducción de dimensionalidad.  
- Implementar **K-means** y **clustering jerárquico**.  
- Evaluar los resultados mediante métricas como **GAP** y **Silhouette**.  
- Visualizar los resultados de forma representativa y analizar su coherencia con las hipótesis iniciales.

---

## Dataset
**Fuente:** [Smart Farming Crop Yield Dataset – Kaggle](https://www.kaggle.com/datasets/atharvasoundankar/smart-farming-sensor-data-for-yield-prediction)

El dataset contiene información sensorial asociada a cultivos, incluyendo variables como:
- Humedad del suelo  
- pH del suelo  
- Temperatura  
- Precipitación  
- Horas de luz solar  
- Tipo de cultivo (variable objetivo)

---

## Tecnologías utilizadas
- **Python 3.x**  
- **Pandas**, **NumPy**  
- **Matplotlib**, **Seaborn**, **Plotly**  
- **Scikit-learn**  
- **Jupyter Notebook**

---

## Metodología

### 1. Análisis exploratorio (EDA)
- Revisión de distribuciones, correlaciones, valores faltantes y outliers.  
- Limpieza y normalización de datos.

### 2. Reducción de dimensionalidad
- Aplicación de **PCA**, **Isomap** y **t-SNE**.  
- Análisis de la varianza acumulada y representación en 2D/3D.

### 3. Clustering
- **K-means** con análisis del número óptimo de clusters (método del codo, GAP).  
- **Clustering jerárquico** con score de **Silhouette**.  
- Visualización tridimensional de clusters.

### 4. Conclusiones
- Interpretación de los resultados obtenidos y evaluación de la coherencia con las hipótesis iniciales.

