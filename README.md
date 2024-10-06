# Transformacion-de-datos
Repositorio donde se encuentra el código dedicado a la transformación de los datos de PDFs a datos que puedan ser explotados

En este repositorio se encuentran los siguientes archivos:
- carga_datos_cloud.ipynb: Este código se encarga de subir todos los pdfs que se van a transformar al bucket correspondiente en Google Cloud. Se ha hecho de esta forma debido a que al intentar subir de forma tradicional una cantidad tan grande de pdfs (12000-13000) recibiamos errores de subida. Al hacerlo por código nos garantizamos de que se suba correctamente
- extraccion_IA.ipynb: Notebook donde se leen todos los PDFs de un bucket de Google Cloud y se procesan de tal forma que puedan ser utilizados posteriormente en el proyecto
