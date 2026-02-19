# BASE CCVM 2024 - Cardiovascular Risk Prediction

Este repositorio contiene el desarrollo metodológico y analítico del Trabajo Fin de Máster (TFM) orientado a la construcción y evaluación de modelos predictivos de riesgo cardiovascular a partir de datos clínicos reales.

El proyecto integra análisis exploratorio de datos, preprocesamiento, modelado mediante técnicas de Machine Learning supervisado y evaluación del desempeño de los modelos, con el objetivo de apoyar la identificación temprana de pacientes en riesgo.

## Dataset

La base de datos CCVM2024_ClinicalDataset_Anonymized fue proporcionada por una Institución Prestadora de Servicios de Salud (IPS) en Colombia y corresponde a registros clínicos anonimizados de pacientes atendidos en programas de control y prevención cardiovascular.

El conjunto de datos está compuesto por:

- 7.339 registros de pacientes
- 25 variables clínicas y sociodemográficas

Incluye información relacionada con edad, sexo, indicadores antropométricos, perfil lipídico, variables metabólicas y otros factores de riesgo cardiovascular relevantes.

## Consideraciones éticas y confidencialidad

Por razones de confidencialidad, protección de datos personales y cumplimiento de la normativa vigente en materia de datos en salud, el conjunto de datos ha sido previamente anonimizado. Su uso se limita a fines académicos y de investigación.

## Metodología

El flujo de trabajo desarrollado en el proyecto comprende:

- Análisis exploratorio de datos (EDA)
- Limpieza y preprocesamiento de variables clínicas
- Tratamiento de valores faltantes y estandarización
- Construcción de modelos predictivos: Regresión Logística, Random Forest y XGBoost
- Evaluación mediante métricas de desempeño y curvas ROC
- Visualización e interpretación de resultados

## Tecnologías utilizadas

- Python (Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn)
- Jupyter Notebook / Google Colab
- GitHub
  
## Estructura del repositorio

- **`CCVM2024_ClinicalDataset_Anonymized.xlsx`**: Dataset clínico anonimizado utilizado en el estudio
- **`CCVM2024_ML_Pipeline.ipynb`**: Notebook principal con todo el flujo analítico y de modelado
- **`README.md`**: Documentación del proyecto
