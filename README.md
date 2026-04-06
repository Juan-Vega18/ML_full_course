# 🤖 ML Full Course — Aprendizaje de Machine Learning

Repositorio personal de aprendizaje de **Machine Learning**: teoría, ejercicios prácticos y proyectos propios.

---

## 🎯 Objetivo

Documentar mi aprendizaje de Machine Learning desde los fundamentos hasta la construcción de proyectos reales. El curso es de nivel básico-intermedio e incluye:

- Comprensión de la teoría matemática detrás de cada algoritmo.
- Implementaciones prácticas en Python (NumPy, Pandas, Scikit-learn, TensorFlow/Keras).
- Proyectos aplicados con datasets reales.

---

## 📂 Estructura del Repositorio

```
ML_full_course/
│
├── 01_Fundamentos/                  # Bases de ML, Python científico y estadística
│   ├── README.md
│   ├── 01_intro_ml.ipynb            # ¿Qué es el Machine Learning?
│   ├── 02_numpy_pandas.ipynb        # NumPy y Pandas esenciales
│   └── 03_visualizacion.ipynb       # Matplotlib y Seaborn
│
├── 02_Aprendizaje_Supervisado/      # Regresión y Clasificación
│   ├── README.md
│   ├── 01_regresion_lineal.ipynb
│   ├── 02_regresion_logistica.ipynb
│   ├── 03_arboles_decision.ipynb
│   ├── 04_random_forest.ipynb
│   └── 05_svm.ipynb
│
├── 03_Aprendizaje_No_Supervisado/   # Clustering y Reducción de Dimensionalidad
│   ├── README.md
│   ├── 01_kmeans.ipynb
│   ├── 02_dbscan.ipynb
│   └── 03_pca.ipynb
│
├── 04_Redes_Neuronales/             # Deep Learning con Keras/TensorFlow
│   ├── README.md
│   ├── 01_perceptron.ipynb
│   ├── 02_redes_neuronales_densas.ipynb
│   └── 03_intro_cnn.ipynb
│
└── Proyectos/                       # Proyectos completos con datasets reales
    ├── README.md
    └── P01_prediccion_precios/      # Proyecto 1: Predicción de precios de casas
        ├── README.md
        └── prediccion_precios.ipynb
```

---

## 🗺️ Ruta de Aprendizaje

| # | Módulo | Temas | Estado |
|---|--------|-------|--------|
| 1 | [Fundamentos](./01_Fundamentos/) | Python científico, estadística básica, visualización | 🔄 En progreso |
| 2 | [Aprendizaje Supervisado](./02_Aprendizaje_Supervisado/) | Regresión, clasificación, árboles, SVM | ⏳ Pendiente |
| 3 | [Aprendizaje No Supervisado](./03_Aprendizaje_No_Supervisado/) | Clustering, PCA | ⏳ Pendiente |
| 4 | [Redes Neuronales](./04_Redes_Neuronales/) | Perceptrón, DNN, CNN | ⏳ Pendiente |
| 5 | [Proyectos](./Proyectos/) | Proyectos con datos reales | 🔄 En progreso |

---

## 🛠️ Tecnologías

| Librería | Uso |
|----------|-----|
| `Python 3.10+` | Lenguaje principal |
| `NumPy` | Álgebra lineal y operaciones numéricas |
| `Pandas` | Manipulación y análisis de datos |
| `Matplotlib / Seaborn` | Visualización |
| `Scikit-learn` | Algoritmos de ML clásicos |
| `TensorFlow / Keras` | Redes neuronales y Deep Learning |
| `Jupyter Notebook` | Entorno de desarrollo interactivo |

---

## ⚙️ Instalación y Uso

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/Juan-Vega18/ML_full_course.git
   cd ML_full_course
   ```

2. **Crear entorno virtual e instalar dependencias:**
   ```bash
   python -m venv venv
   source venv/bin/activate        # Linux/Mac
   # venv\Scripts\activate         # Windows

   pip install -r requirements.txt
   ```

3. **Abrir Jupyter:**
   ```bash
   jupyter notebook
   ```

---

## 📌 Proyectos Destacados

| # | Proyecto | Descripción | Algoritmo |
|---|----------|-------------|-----------|
| 1 | [Predicción de Precios de Casas](./Proyectos/P01_prediccion_precios/) | Predecir el precio de viviendas usando características del inmueble | Regresión Lineal / Random Forest |

---

## 📚 Recursos y Referencias

- [Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow — Aurélien Géron](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)
- [Documentación de Scikit-learn](https://scikit-learn.org/stable/)
- [Documentación de TensorFlow](https://www.tensorflow.org/)
- [Kaggle — Datasets y competencias](https://www.kaggle.com/)

---

## 📈 Progreso Personal

- [x] Configurar el repositorio
- [x] Definir estructura de carpetas
- [ ] Completar módulo de Fundamentos
- [ ] Completar módulo de Aprendizaje Supervisado
- [ ] Completar módulo de Aprendizaje No Supervisado
- [ ] Completar módulo de Redes Neuronales
- [ ] Completar Proyecto 1: Predicción de Precios de Casas

---

## 📄 Licencia

Este repositorio está bajo la licencia [MIT](./LICENSE). Los notebooks y proyectos son de uso libre para fines educativos.
