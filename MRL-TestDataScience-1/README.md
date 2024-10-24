# MRL-TestDataScience-1
Este proyecto consiste en la clasificación de automóviles utilizando el `Automobile` Dataset de UCI Machine Learning Repository, disponible desde el siguiente enlace > https://archive.ics.uci.edu/dataset/10/automobile

Se ha escogido este Dataset ya que en la primera entrevista se mencionó el enfoque de trabajo en un cliente del sector automoción.

## Instalación
1. Clonar o descargar el repositorio
2. En mi caso, he creado un entorno virtual
3. Instalar las dependencias> pip install -r requirements.txt

## Estructura del proyecto

automobile > Carpeta que contiene toda la información descargada del Dataset
scripts:
    · EDA.ipynb > Este Jupyter Notebook contiene el código necesario para llevar a cabo el análisis preliminar, la limpieza y las visualizaciones que he considerado óptimas para el estudio del Dataset 'Automobile' para intentar determinar relaciones entre las características de los coches.
    El fichero 'imports-85.data' dentro de la carpeta 'automobile' contiene los datos sobre los que trabajaremos, y el fichero 'imports-85.names' contiene información general.
    · classification_models > Este Notebook contiene el código utilizado para entrenar y evaluar modelos de clasificación. Los modelos seleccionados incluyen Logistic Regression, Random Forest y XGBoost, entre otros. Se detallan las métricas de evaluación (precisión, recall, F1-score, y AUC-ROC) y se justifica la selección del mejor modelo en función de su rendimiento. También se incluye la implementación de pipelines para el preprocesamiento de datos y la evaluación cruzada de los modelos.

README.md
requirements.txt > Archivo que contiene las dependencias necesarias para ejecutar el código del proyecto. Las principales bibliotecas incluyen pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost