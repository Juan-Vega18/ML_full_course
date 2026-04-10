# 📗 Módulo 2 — Aprendizaje Supervisado

El aprendizaje supervisado es la rama más usada del ML. El modelo aprende la relación entre entradas (features) y salidas (labels) usando datos etiquetados.

## Contenido

| Notebook | Descripción |
|----------|-------------|
| `01_regresion_lineal.ipynb` | Regresión lineal simple y múltiple, mínimos cuadrados |
| `02_regresion_logistica.ipynb` | Clasificación binaria y multiclase con regresión logística |
| `03_arboles_decision.ipynb` | Árboles de decisión: CART, profundidad, poda |
| `04_random_forest.ipynb` | Ensambles: bagging, Random Forest, importancia de características |
| `05_svm.ipynb` | Support Vector Machines: margen máximo, kernels |

## Conceptos Clave

- **Regresión**: predecir un valor continuo (ej. precio de una casa).
- **Clasificación**: predecir una categoría (ej. spam o no spam).
- **Overfitting / Underfitting**: ajuste excesivo vs. insuficiente.
- **Train / Validation / Test split**: separar datos para entrenar, validar y evaluar.
- **Métricas de evaluación**:
  - Regresión: MAE, MSE, RMSE, R²
  - Clasificación: Accuracy, Precision, Recall, F1-score, AUC-ROC

## Algoritmos Cubiertos

| Algoritmo | Tipo | Ventajas |
|-----------|------|----------|
| Regresión Lineal | Regresión | Simple, interpretable |
| Regresión Logística | Clasificación | Probabilístico, eficiente |
| Árbol de Decisión | Ambos | Visual, no paramétrico |
| Random Forest | Ambos | Robusto, reduce overfitting |
| SVM | Ambos | Efectivo en alta dimensión |
