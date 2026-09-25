# Análisis de la Deserción Escolar en Bolivia - EH2025

## Descripción

Proyecto desarrollado utilizando los microdatos de la Encuesta de Hogares 2025
del Instituto Nacional de Estadística de Bolivia.

El objetivo es analizar factores sociodemográficos, económicos y geográficos
asociados a la no asistencia escolar en personas de 6 a 19 años.

## Caso de estudio

Caso 1: Análisis de la Deserción Escolar en Bolivia.

Variable principal:

- Asistencia_Escolar
- 1 = Asiste
- 0 = No asiste

Para el modelado predictivo se creó:

- Riesgo_Desercion
- 1 = No asiste
- 0 = Asiste

## Datos utilizados

Se utilizaron:

- EH2025_Persona
- EH2025_Vivienda

Los datos fueron integrados mediante el identificador anonimizado del hogar.

Dataset analítico final: 10.448 registros.

## Análisis realizado

- Limpieza y preprocesamiento
- Ingeniería de características
- Análisis exploratorio de datos
- Visualizaciones estáticas e interactivas
- Mapa interactivo
- Clustering K-Means
- Regresión Logística
- Random Forest
- Evaluación con Accuracy, Precision, Recall, F1 y AUC-ROC
- Matrices de confusión
- Importancia de variables

## Principales resultados

La tasa observada de no asistencia escolar fue de 5,21%.

El área rural presentó una tasa de 8,93%, frente a 4,00% del área urbana.

La no asistencia aumenta considerablemente en las edades mayores:
18 años = 18,73% y 19 años = 37,18%.

La Regresión Logística obtuvo:

- Accuracy: 87,08%
- Precision: 26,93%
- Recall: 86,24%
- F1: 41,05%
- AUC-ROC: 92,18%

Random Forest obtuvo:

- Accuracy: 94,64%
- Precision: 47,37%
- Recall: 24,77%
- F1: 32,53%
- AUC-ROC: 90,86%

## Estructura

Proyecto_EH2025_ML_Caso1/

- data/
  - dataset_procesado.csv
- notebooks/
  - EH2025_Analisis_ML.ipynb
- outputs/
  - storytelling.pdf
  - predicciones.csv
  - resultados_modelos.csv
  - top10_variables_random_forest.csv
  - perfil_clusters.csv
  - mapas y visualizaciones interactivas
  - imagenes/
- docs/
  - README.md
- requirements.txt

## Fuente

Instituto Nacional de Estadística de Bolivia.
Encuesta de Hogares 2025 (EH2025).

## Autor

Daysi Maribel Quispe Guarachi
