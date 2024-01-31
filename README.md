# OPTIMIZACIÓN DE LA TÁCTICA EN FÚTBOL MEDIANTE TÉCNICAS DE MACHINE LEARNING
Los datos originales se encuentran en la carpeta "database"
1. XValue: Contiene todas las carpetas con los datos descargados
2. FBref: Contiene las carpetas y el archivo "scraping.ipynb" para la colección de esta fuente.

## Preprocesamiento de datos 
Los archivos para el preprocesamiento de datos son: "fbref_clean.ipynb" y "xvalue_clean.ipynb". Los archivos .csv se generaron en la carpeta "final_data" con el nombre de "fbref.csv" y "xvalue.csv"

## Homogenización de los datos
El archivo para la homogenización de los datos es "rolling.ipynb", este genera el archivo "rolled_data.csv" que está almacenado en la carpeta "final_data"

## Modelos 
1. Los modelos básicos se encuentran en el archivo "base_models.ipynb"
2. Las redes neuronales y XGBoost se encuentra en el archivo "neural_networks.ipynb"
