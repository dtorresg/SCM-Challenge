# SCM-Challenge
Este repositorio contiene la solución al desafío técnico para el cargo de Data Scientist en CM LATAM.

## Ejecución
Sigue los siguientes pasos para correr el notebook:

## Crear un ambiente virtual
En la raíz del proyecto, ejecuta el siguiente comando para crear un ambiente virtual:

```
python3 -m venv venv
```
## Activar el ambiente virtual

En Linux/MacOS:
```
source venv/bin/activate
```
En Windows:

```
.\venv\Scripts\activate
```
### Instalar las dependencias
Con el ambiente virtual activo, instala todas las dependencias necesarias usando el archivo requirements.txt:

```
pip install -r requirements.txt
```
## Correr el servidor de MLflow
En otra pestaña de tu terminal (con el ambiente virtual activo), inicia el servidor de MLflow para realizar el seguimiento del entrenamiento de los modelos:

```
mlflow server
```
## Ejecutar el notebook
Abre y ejecuta el notebook en tu entorno de Jupyter. Puedes abrir el entorno con:
```
jupyter notebook
```