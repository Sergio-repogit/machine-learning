# Machine Learning

Repositorio que recoge implementaciones de modelos de **Machine Learning supervisado y no supervisado** desarrollados principalmente en **R**, con enfoque aplicado a análisis de datos reales.

El objetivo es mostrar el flujo completo de trabajo: preprocesamiento, modelización, validación y comparación de modelos.

---

## Estructura del repositorio

```
machine-learning/
├── supervised-learning/
│   ├── regression/
│   └── classification/
└── unsupervised-learning/
    ├── clustering/
    └── dimensionality-reduction/
```
Todos los proyectos empiezan con las indicaciones que se realizaran en dicho archivo
---

## Supervised Learning

### Regression

Proyectos de modelización predictiva sobre variables continuas.

**Proyectos incluidos:**

* `statistical_modelling_datos_eco_dataset`
* `statistical_modelling_usa_dataset` (incluye dataset `USA.txt`)

**Modelos implementados:**

* Regresión lineal
* Regresión polinómica
* Splines
* Step functions

**Objetivo:**
Evaluar relaciones entre variables económicas y comparar técnicas de regresión.

---

### Classification

Proyectos de clasificación supervisada sobre distintos datasets.

**Proyectos incluidos:**

* `classification_models_BreastCancer`
* `classification_models_iris`
* `SVM_KNN_Decision_Tree_dataset_Default`

**Modelos implementados:**

* Regresión logística
* Árboles de decisión
* Random Forest
* Support Vector Machines (SVM)
* K-Nearest Neighbors (KNN)

**Objetivo:**
Comparar el rendimiento de distintos clasificadores y analizar su capacidad predictiva.

---

## Unsupervised Learning

### Clustering

Proyectos de aprendizaje no supervisado orientados a segmentación de datos.

**Proyectos incluidos:**

* `Clusters_jerarquico_dataset_Propia`
* `Clusters_no_jerarquico_dataset_cloud`
* `Clusters_no_jerarquico_dataset_Propia`

**Modelos implementados:**

* K-means
* Gaussian Mixture Models (GMM)
* DBSCAN
* Clustering jerárquico
* Spectral clustering

**Objetivo:**
Identificar estructuras latentes en los datos y comparar métodos de clustering.

---

### Dimensionality Reduction

Proyectos centrados en reducción de dimensionalidad.

**Proyectos incluidos:**

* `PCA_dataset_AppXperience` (incluye dataset `datos_pca`)

**Técnicas implementadas:**

* Principal Component Analysis (PCA)

**Objetivo:**
Reducir la dimensionalidad preservando la máxima varianza y facilitar la visualización de datos.

---

## Tecnologías utilizadas

* R
* tidyverse
* caret
* Funciones propias
* randomForest
* cluster
* factoextra

---

## Autor

Sergio Mínguez Cruces
Grado en Matemáticas mención Data Science & Machine Learning
