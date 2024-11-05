# MRL-TestDataScience-2
Este proyecto consiste en el análisis de una serie temporal multivariante de tipo no financiero donde la variable a predecir no tenga estacionalidad. Realizaremos las comprobaciones necesarias para afirmar que la serie temporal es no-estacional y aplicaremos algunos modelos de ML/series temporales para predecir periodos temporales como se indica en el enunciado de la práctica.

El dataset sobre el que vamos a trabajar está disponible en la página web de CNMC Data desde el siguiente enlace: https://data.cnmc.es/energia/productos-petroliferos/estadistica-de-productos-petroliferos/estadistica-petroleo

## Instalación
1. Clonar o descargar el repositorio en local
2. En mi caso, he creado dos entornos virtuales: 'env2' para instalar las bibliotecas y ejecutar los notebooks 'load_dataset.ipynb' y 'regression_model.ipynb' que utilizan Python=3.12.7, y 'env3' para instalar las bibliotecas y ejecutar el notebook 'LSTM_model.ipynb' que utiliza Python=3.10 por compatibilidad de versiones con las bibliotecas de TensorFlow.
3. Instalar las dependencias> pip install -r requirements.txt

## Estructura del proyecto

- data_biodiesel.csv> Dataset preparado para ejecutar los modelos de ML basados en LSTM
- dataset4regression.csv> Dataset preparado para ejeuctar los modelos de series temporales
- ds_2943_1.csv> Dataset original descargado desde la web de CNMC Data
- README.md
- requirements_env2.txt> Archivo que contiene las dependencias necesarias para ejecutar los dos primeros scripts
- requirements_LSTM.txt> Archivo que contiene las depedndencias necesarias para ejecutar el último script
- Secuencia de ejecución de los scripts:
    1. load_dataset.ipynb
    2. regression_model.ipynb
    3. LSTM_model.ipynb