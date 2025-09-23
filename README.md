# Análisis de la Generación de Residuos Sólidos en Perú
Este proyecto utiliza técnicas de minería de datos para analizar la generación de residuos sólidos en diversos distritos de Perú. Se emplearon algoritmos de **K-Means** y **K-Prototypes** para segmentar los distritos en función de su población y cantidad de residuos generados.

## Archivos:
- **Código**: Análisis y limpieza de datos en Google Colab (`.ipynb`).
- **Datos**: [Dataset de residuos sólidos] diccionario de datos. https://github.com/PriscilaRojasS/Analisis_generacion_residuos_solidos_municipales/raw/refs/heads/main/dataset_residuos_final.xlsx
- **Diccionario de datos**: [Diccionario] https://github.com/PriscilaRojasS/Analisis_generacion_residuos_solidos_municipales/raw/refs/heads/main/C.%20Formato_DiccionarioDatos_Generacion%20anual%20de%20residuos%20s%C3%B3lidos%20domiciliarios%20y%20municipales.xlsx
- 
## Metodología:
Se siguió la metodología **KDD** para la selección, preprocesamiento y modelado de los datos, y se emplearon técnicas de clustering para la segmentación de distritos.

## Repositorio:
El código se ejecuta en Google Colab y se presenta en este repositorio de GitHub.

## Cómo ejecutar:
1. Clona el repositorio.
2. Abre el archivo `.ipynb` en Google Colab.
3. Ejecuta las celdas de código.

## Licencia:
Este proyecto es de uso académico.

## Resultados

A continuación se presentan los **resultados del análisis exploratorio** y los **gráficos** generados:

### Análisis Exploratorio:
- **Distribución de datos**: Se ha realizado un análisis descriptivo de las principales variables como población total y generación de residuos. Los datos muestran una **correlación** positiva entre estos dos factores, lo que sugiere que a mayor población, mayor generación de residuos.
  
- **Detección de outliers**: Se identificaron valores atípicos en distritos con poblaciones extremadamente altas (como Lima Metropolitana), los cuales fueron tratados adecuadamente en el preprocesamiento.

### Gráficos:

1. **Fig 1. Relaciones entre variables**  
   Relación positiva muy fuerte entre los indicadores de población y la generación total de residuos.
   En contraste, la generación per cápita municipal presenta correlaciones débiles con la población (r ≈ 0.20–0.26),
   Puedes ver este gráfico a continuación:

   ![Figura1_Relaciones entre variables](https://github.com/PriscilaRojasS/Analisis_generacion_residuos_solidos_municipales/blob/main/Figura1.png?raw=true)

2. **Fig 2. Generación anual de residuos sólidos municipales (Total nacional)**
   La evolución anual presenta una trayectoria creciente entre 2019–2022: el total nacional pasa de 7.77 a 8.43 millones de toneladas, lo que implica un incremento acumulado de ≈8.5%.
   ![Figura2_Genración_anual_residuos](https://github.com/PriscilaRojasS/Analisis_generacion_residuos_solidos_municipales/blob/main/Figura2.png?raw=true)
3.  **Fig 3. Top 5 departamentos por generación anual promedio**
El ranking de generación anual promedio muestra una alta concentración en Lima, con más de 3.5 millones de toneladas por año, lo que representa una magnitud muy superior al resto del país.
   ![Fig 3Top 5 departamentos_generaciónanualpromedio](https://github.com/PriscilaRojasS/Analisis_generacion_residuos_solidos_municipales/blob/main/Figura3.png?raw=true)

4.  **Fig 4. Generación municipal de residuos per cápita por día según clasificación MEF**
   El análisis por clasificación municipal MEF revela grandes diferencias en la generación per cápita diaria de residuos. Las municipalidades de categoría C presentan el valor más alto (188.4 t/día por habitante), muy por encima de las categorías A (70.1) y D (41.3). En contraste, las categorías B, E, F y G registran valores considerablemente menores (entre 0.6 y 5.1).
    ![Fig 4. Generación municipal_residuos](https://github.com/PriscilaRojasS/Analisis_generacion_residuos_solidos_municipales/blob/main/Figura4.png?raw=true)

5.  **Fig 5. Relación entre Población y Generación de Residuos**
   El gráfico muestra una fuerte correlación positiva entre la población total y la cantidad de residuos sólidos generados. A medida que aumenta la población, también lo hacen los residuos municipales y domiciliarios.
    ![Fig 5. Relacion_poblacion_generacionr](https://github.com/PriscilaRojasS/Analisis_generacion_residuos_solidos_municipales/blob/main/Figura5.png?raw=true)
6. **Fig 6. Métodos para determinar el tamaño de k (número de clusters)**
   ![Fig 6. MétodostamañoK](https://github.com/PriscilaRojasS/Analisis_generacion_residuos_solidos_municipales/blob/main/Figura6.png?raw=true)
8. **Fig 7. Clusters: Población vs. Generación de Residuos**
   ![Fig7.Clusters](https://github.com/PriscilaRojasS/Analisis_generacion_residuos_solidos_municipales/blob/main/Figura7.png?raw=true)

    


