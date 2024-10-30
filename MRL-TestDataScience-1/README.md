# MRL-TestDataScience-1
Este proyecto consiste en la clasificación de automóviles utilizando el `Automobile` Dataset de UCI Machine Learning Repository, disponible desde el siguiente enlace > https://archive.ics.uci.edu/dataset/10/automobile

## Instalación
1. Clonar o descargar el repositorio en local
2. En mi caso, he creado un entorno virtual ('env1') para instalar las bibliotecas y ejecutar los scripts
3. Instalar las dependencias> pip install -r requirements.txt

## Estructura del proyecto

- automobile> Carpeta que contiene toda la información descargada del Dataset
- dataset_EDA.csv> Dataset limpio que se obtiene tras la ejecución completa del EDA.ipynb
- env1> Entorno virtual con las bibliotecas necesarias instaladas
- README.md
- requirements.txt> Archivo que contiene las dependencias necesarias para ejecutar el código del proyecto. Las principales bibliotecas incluyen pandas, numpy, scikit-learn, matplotlib, seaborn
- Secuencia de ejecución de los scripts:
    1. EDA.ipynb> Este Jupyter Notebook contiene el código necesario para llevar a cabo el análisis preliminar, la limpieza y las visualizaciones que he considerado óptimas para el estudio del Dataset 'Automobile' para intentar determinar relaciones entre las características de los coches.
    El fichero 'imports-85.data' dentro de la carpeta 'automobile' contiene los datos sobre los que trabajaremos, y el fichero 'imports-85.names' contiene información general.
    2. classification_models> Este Notebook contiene el código utilizado para entrenar y evaluar modelos de clasificación. Los modelos seleccionados finalmente son: Logistic Regression, Random Forest, KNN y SVM, entre otro modelos que se configuraron o tuvieron en cuenta. Se detallan las métricas de evaluación (precisión, recall, F1-score y AUC-ROC) y se justifica la selección del mejor modelo en función de su rendimiento. También se incluye la implementación de pipelines para el preprocesamiento de datos y la evaluación cruzada de los modelos.
    3. DevOps_integration.ipynb> Contiene el código necesario para cargar el modelo y realizar predicciones con nuevos datos que se añadan en el futuro.