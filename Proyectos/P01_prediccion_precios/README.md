# 🏠 Proyecto 1 — Predicción de Precios de Casas

## Descripción del Problema

Dado un conjunto de características de viviendas (superficie, número de habitaciones, ubicación, etc.), predecir el **precio de venta** de la casa.

Este es un problema clásico de **regresión supervisada** y es uno de los proyectos de introducción más populares en Machine Learning.

## Dataset

- **Fuente**: [California Housing Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html) (disponible directamente en scikit-learn) o [Kaggle — House Prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).
- **Variables**: superficie habitable, número de habitaciones, antigüedad, ubicación geográfica, etc.
- **Target**: precio de la vivienda (valor continuo).

## Metodología

1. **Análisis Exploratorio de Datos (EDA)**: distribuciones, correlaciones, valores nulos.
2. **Preprocesamiento**: manejo de nulos, encoding de variables categóricas, escalado.
3. **Modelado**:
   - Regresión Lineal (baseline)
   - Random Forest Regressor
4. **Evaluación**: MAE, RMSE, R².
5. **Conclusiones y mejoras posibles**.

## Resultados

> *(Se completará al finalizar el notebook)*

| Modelo | MAE | RMSE | R² |
|--------|-----|------|----|
| Regresión Lineal | — | — | — |
| Random Forest | — | — | — |

## Archivos

| Archivo | Descripción |
|---------|-------------|
| `prediccion_precios.ipynb` | Notebook principal con el análisis completo |
| `data/` | (local, no en git) — dataset descargado |
