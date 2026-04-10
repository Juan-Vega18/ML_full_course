# 📙 Módulo 3 — Aprendizaje No Supervisado

En el aprendizaje no supervisado no existen etiquetas. El modelo descubre patrones, agrupaciones o estructuras ocultas en los datos.

## Contenido

| Notebook | Descripción |
|----------|-------------|
| `01_kmeans.ipynb` | Algoritmo K-Means: agrupamiento por centroides |
| `02_dbscan.ipynb` | DBSCAN: clustering por densidad, detección de outliers |
| `03_pca.ipynb` | Análisis de Componentes Principales (PCA): reducción de dimensionalidad |

## Conceptos Clave

- **Clustering**: agrupar puntos similares sin etiquetas previas.
- **Reducción de dimensionalidad**: comprimir datos manteniendo la mayor información posible.
- **Varianza explicada** (PCA): proporción de información retenida tras la transformación.
- **Inercia** (K-Means): suma de distancias al centroide más cercano — método del codo para elegir K.
- **Outliers**: puntos anómalos que no pertenecen a ningún clúster (DBSCAN los detecta como ruido).

## Algoritmos Cubiertos

| Algoritmo | Tipo | Ventajas |
|-----------|------|----------|
| K-Means | Clustering | Rápido, escalable |
| DBSCAN | Clustering | Detecta outliers, formas arbitrarias |
| PCA | Reducción | Reduce ruido, acelera otros modelos |
