README JUAN
- Modificar el archivo .gitignore
- Añadir y modificar el archivo "requirements.txt"
- Eliminar en el archivo src/main.py el "src" superfluo de:
	from data_loader import load_data, preprocess_data
	from evaluate import evaluate
	from model import train_model
- Cambiar la URL de MLFLOW_URI = "http://57.151.65.76:5000"
- Modificar (con nuestro propio nombre identificativo) el EXPERIMENT_NAME="jumarfra-adult-income"
- Crear una variable de usuario/sistema dentro de Windows
	AZURE_STORAGE_CONNECTION_STRING
- Instalar los requirements en local
- Se crea un entorno virtual para favorecer la puesta en marcha del modelo en local (opcional)
- Creamos nueva branch (para no trabajar en la rama main)
- Creamos las carpetas .github/workflows
- Dentro de /workflows, creamos integration.yml -> Para la automatización de pipelines (dentro de actions) 