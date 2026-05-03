# Organización de modelos

Esta carpeta contiene artefactos entrenados y tablas de resultados.

## Estructura

```text
models/
├── reports/
├── stacking/
├── supervised/
└── unsupervised/
```

## reports/

Tablas CSV con comparativas de modelos:

- `model_comparison.csv`: resultados principales del Grid Search supervisado.
- `model_comparison_retrained.csv`: resultados de modelos reentrenados con mejores hiperparámetros.
- `model_comparison_with_stacking.csv`: comparativa antigua con stacking.
- `model_comparison_06_stacking.csv`: comparativa final del notebook `06_Stacking.ipynb`.

## supervised/

Modelos supervisados de fraude:

- `best_fraud_pipeline.joblib`: mejor pipeline supervisado guardado.
- `retrained_best_models/`: modelos reentrenados con los mejores hiperparámetros.

## stacking/

Modelos de stacking y ensembles:

- `stacking_fraud_pipeline.joblib`: stacking inicial.
- `stacking_prefit_fraud_pipeline.joblib`: stacking generado en `06_Stacking.ipynb`.

## unsupervised/

Artefactos no supervisados:

- `kmeans_unsupervised_pipeline.joblib`: pipeline final de K-Means.
- `dbscan_unsupervised_artifact.joblib`: preprocesador, SVD, etiquetas y resultados de DBSCAN.

## Modelo recomendado

El modelo principal recomendado es:

```text
models/supervised/retrained_best_models/LightGBM_con_smote.joblib
```

porque obtuvo el mejor PR-AUC real y mejor equilibrio para detección de fraude.
