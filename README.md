Este repositorio contiene el código fuente y el análisis desarrollado por el Grupo 3 para el curso de Data Mining. El proyecto integra datos abiertos (MINAM, MEF, INEI) para diagnosticar, segmentar y predecir la generación de residuos sólidos en los distritos del Perú.

Objetivos

Diagnosticar el estado actual de la generación de residuos a nivel nacional.

Segmentar los distritos en grupos homogéneos (Clusters) según patrones socioeconómicos y de generación.

Predecir la generación anual de residuos utilizando modelos de Machine Learning.

Tecnologías y Metodología

Lenguaje: Python 3.x

Librerías Clave: pandas, scikit-learn, plotly, streamlit, openpyxl.

Metodología:

Preprocesamiento: Limpieza, imputación y transformación de variables (StandardScaler, OneHotEncoder).

Clustering (No Supervisado): Algoritmo K-Means con reducción de dimensionalidad (PCA) para identificar 4 perfiles de distritos.

Regresión (Supervisado): Modelo Random Forest para estimar la generación total anual (Ton/Año).

Estructura del Proyecto

dataset_residuos.xlsx: Dataset consolidado con variables sociodemográficas, económicas y de residuos.

ENTREGA_FINAL_G3_DM_BETA_1.ipynb: Notebook principal con el análisis exploratorio (EDA), entrenamiento de modelos y validación.

