# Detección de Fraude Bancario mediante Machine Learning

## Descripción del Proyecto

Este Trabajo de Fin de Grado (TFG) tiene como objetivo desarrollar un sistema de detección de fraude en transacciones bancarias utilizando técnicas de Machine Learning.

El proyecto aborda el problema del fraude como una tarea de clasificación binaria altamente desbalanceada, aplicando técnicas avanzadas de preprocesamiento, modelado e interpretabilidad.

---

## Objetivos

* Analizar y comprender el comportamiento de las transacciones fraudulentas.
* Realizar un Análisis Exploratorio de Datos (EDA) completo.
* Tratar el desbalanceo de clases mediante técnicas como SMOTE.
* Construir modelos predictivos robustos.
* Implementar un modelo de **stacking** para mejorar el rendimiento.
* Aplicar técnicas de **clustering** para identificar patrones ocultos.
* Interpretar los modelos mediante herramientas como LIME.

---

## Librerías Utilizadas

### Análisis y manipulación de datos

* **pandas** → Manipulación y limpieza de datos.
* **numpy** → Operaciones numéricas y estructuras eficientes.

### Visualización

* **matplotlib** → Gráficos básicos.
* **seaborn** → Visualización avanzada y análisis estadístico.
* **missingno** → Análisis de valores nulos.

### Análisis Exploratorio (EDA)

* **ydata-profiling** → Generación automática de informes.
* **scipy** → Estadística avanzada.

### Machine Learning

* **scikit-learn** → Modelos, métricas y pipelines.
* **xgboost** → Modelo basado en boosting de alto rendimiento.
* **lightgbm** → Algoritmo eficiente para grandes datasets.
* **catboost** → Especialmente útil con variables categóricas.

### Desbalanceo de clases

* **imbalanced-learn** → Implementación de SMOTE y otras técnicas.

### Clustering

* **scikit-learn** → KMeans, DBSCAN, etc.
* **yellowbrick** → Visualización de resultados de clustering.

### Interpretabilidad

* **lime** → Explicación local de predicciones del modelo.

### Utilidades

* **joblib** → Serialización de modelos.
* **tqdm** → Barras de progreso.
* **scikit-plot** → Métricas visuales (ROC, matrices, etc.).

---

## Metodología

1. **Carga y limpieza de datos**
2. **Análisis Exploratorio de Datos (EDA)**
3. **Preprocesamiento**

   * Escalado
   * Codificación
4. **Tratamiento del desbalanceo (SMOTE)**
5. **Entrenamiento de modelos base**
6. **Construcción de modelo de Stacking**
7. **Clustering para análisis adicional**
8. **Evaluación de modelos**
9. **Interpretabilidad con LIME**

---

## Métricas de Evaluación

Dado el desbalanceo del dataset, se priorizan:

* Precision
* Recall
* F1-score
* ROC-AUC
* PR-AUC

---

## Desafíos del Proyecto

* Alto desbalanceo de clases.
* Riesgo de overfitting.
* Interpretabilidad de modelos complejos.
* Selección adecuada de métricas.

---

## Resultados Esperados

* Modelo robusto capaz de detectar fraude con alta precisión.
* Identificación de patrones relevantes en las transacciones.
* Explicabilidad de las predicciones del modelo.

---

## Estructura del Proyecto

```
├── data/
├── src/
├── notebooks/
├── models/
├── README_EN.md
├── requirements.txt
└── README.md
```

---

## Autor

Trabajo desarrollado como parte del Trabajo de Fin de Grado en Ciencia de Datos, por martina Blay y Aldán García
