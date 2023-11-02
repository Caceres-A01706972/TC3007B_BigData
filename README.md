# TC3007B_BigData
Repositorio para el módulo de Big Data de TC3007C

# ENTREGABLE 1
Este proyecto implementa un sistema de recomendación de películas utilizando PySpark, una biblioteca de procesamiento de datos y aprendizaje automático distribuido de Apache Spark.
## Descripción
El objetivo de este proyecto es recomendar películas similares en función de las descripciones de las películas. Utiliza el procesamiento de texto y la similitud de coseno para encontrar películas con descripciones similares. El flujo de trabajo general incluye:

1. Cargar y preprocesar un conjunto de datos de películas que incluye títulos y descripciones.
2. Aplicar tokenización y eliminación de palabras vacías (stop words) en las descripciones.
3. Utilizar TF-IDF (Term Frequency-Inverse Document Frequency) para representar las descripciones de películas como vectores numéricos.
4. Calcular la similitud de coseno entre las películas basada en sus vectores de características.
5. Recomendar películas similares a una película de referencia dada por el usuario.

## Visualización Tableau
Link al Dashboard público: https://public.tableau.com/views/Netflix_Dashboard_16988978847550/Netflix?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link
