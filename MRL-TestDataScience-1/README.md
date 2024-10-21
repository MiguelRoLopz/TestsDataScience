# Automobile Dataset - Data Science Test
Este proyecto consiste en la clasificación de automóviles utilizando el `Automobile` Dataset de UCI Machine Learning Repository, disponible desde el siguiente enlace > https://archive.ics.uci.edu/dataset/10/automobile o ejecutando el siguiente código:

        pip install ucimlrepo
        from ucimlrepo import fetch_ucirepo 
        
        ##### fetch dataset 
        automobile = fetch_ucirepo(id=10) 
        
        ##### data (as pandas dataframes) 
        X = automobile.data.features 
        y = automobile.data.targets 
        
        ##### metadata 
        print(automobile.metadata) 
        
        ##### variable information 
        print(automobile.variables) 


## Instalación
1. Clonar el repositorio o descargar el código.
2. Crear un entorno virtual y activarlo:

   ```bash
   python -m venv venv
   venv\Scripts\activate

## Instalación de dependecias necesarias
pip install -r requirements.txt