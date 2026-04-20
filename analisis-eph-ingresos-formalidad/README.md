# Análisis y Modelado Predictivo de Ingresos y Formalidad Laboral (EPH - INDEC)

## Descripción
Este proyecto utiliza datos de la Encuesta Permanente de Hogares (EPH - INDEC) para analizar factores socioeconómicos y construir modelos que permitan predecir la formalidad laboral y los ingresos.

---

## Objetivos
- Analizar patrones socioeconómicos en la población  
- Predecir si un empleo es formal o informal  
- Estimar el nivel de ingresos  
- Identificar variables relevantes en cada modelo  

---

## Procesamiento de datos
- Limpieza de datos (valores nulos, selección de variables)
- Transformación de variables categóricas (dummies)
- Preparación de datos para modelado

---

## Modelos implementados

### Clasificación
- Modelo: k-NN  
- Objetivo: predecir formalidad laboral  
- Resultado: **91,56% de accuracy**

---

### Regresión
- Modelos: regresión multivariada y Ridge  
- Métrica: MSE  
- Selección basada en balance entre error y cantidad de variables  

---

### Clustering
- PCA para reducción de dimensionalidad  
- K-Means y DBSCAN para segmentación socioeconómica  

---

## Resultados
- Identificación de grupos socioeconómicos diferenciados  
- Modelo de clasificación con alto nivel de acierto  
- Identificación de variables relevantes en la determinación de ingresos  

---

## Tecnologías utilizadas
- Python (Pandas, NumPy, Scikit-learn, Seaborn)

---

## Archivos
- `analisis-eph.ipynb`: desarrollo completo del trabajo
- `enunciado-eph.pdf`: consigna del trabajo práctico
- `usu_individual_T325.txt`: base de datos
- `EPH_registro_3T2025.pdf`: información detallada de los campos de la base de datos
