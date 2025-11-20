# Análisis de Residuos Sólidos Municipales en el Perú

Este repositorio contiene el código fuente y el análisis desarrollado por el **Grupo 3** para el curso de **Data Mining**.  
El proyecto integra datos abiertos del **MINAM**, **MEF** e **INEI** para diagnosticar, segmentar y predecir la generación de residuos sólidos en los distritos del Perú.

---

## Objetivos

- Diagnosticar el estado actual de la generación de residuos a nivel nacional.
- Segmentar los distritos en grupos homogéneos (clusters) según patrones socioeconómicos y de generación.
- Predecir la generación anual de residuos utilizando modelos de Machine Learning.

---

## Tecnologías y Metodología

**Lenguaje:**  
- Python 3.x

**Librerías clave:**  
- pandas  
- scikit-learn  
- seaborn  
- matplotlib  
- xgboost  
- streamlit  
- openpyxl  

**Metodología aplicada:**

- Preprocesamiento: Limpieza, imputación de valores y transformación de variables (OneHotEncoder, RobustScaler).
- Clustering (No Supervisado): Algoritmo K-Means con reducción de dimensionalidad (PCA) para identificar perfiles de distritos.
- Regresión (Supervisado): Modelos XGBoost y Random Forest para estimar la generación total anual (Toneladas/año).

---

## Estructura del Proyecto

| Archivo / Carpeta                 | Descripción |
|----------------------------------|-------------|
| `dataset_residuos.xlsx`          | Dataset consolidado con variables socioeconómicas y de residuos a nivel distrital. |
| `ENTREGA_FINAL_G3_DM_BETA_1.ipynb` | Notebook principal con análisis exploratorio (EDA), clustering, regresión y visualización. |
| `app.py`                         | Aplicación interactiva en Streamlit para explorar los datos. |

---



