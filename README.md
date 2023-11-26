# Sentiment Analysis for Amazon Book Reviews 📚 😄

Este proyecto utiliza Apache PySpark para realizar análisis de sentimiento en reviews de libros. El dataset utilizado es de `2.86 GB`.

El DataSet se encuentra en el siguiente link: https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews/data

El objetivo es predecir si un comentario es positivo o negativo mediante un modelo de regresión logística.

## Introducción 🚀

El análisis de sentimiento es una tarea en la que se evalúa la actitud emocional expresada en un texto. En este proyecto, se utiliza PySpark para entrenar un modelo que puede clasificar automáticamente los comentarios en categorías de sentimientos y posteriormente poder hacer predicciones.

## Flujo del Código 💻

1. **Configuración del Entorno:**
   -  Instalar Apache Spark.

2. **Carga y Exploración de Datos:**
   - Lee el conjunto de datos (`Book_rating.csv`).
   - El conjunto de datos fue tomado de Kaggle. El link es el siguiente: https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews/data

3. **Preprocesamiento de Datos:**
   - Limpia y transforma los datos para prepararlos para el análisis.
   - Selecciona las columnas relevantes y maneja los tipos de datos.

4. **Tokenización y Filtrado de Stop Words:**
   - Utiliza Tokenizer y StopWordsRemover para procesar el texto de los comentarios.

5. **Creación del Modelo:**
   - Define y configura un modelo de regresión logística.

6. **Entrenamiento del Modelo:**
   - Divide los datos en conjuntos de entrenamiento y prueba.
   - Entrena el modelo utilizando el conjunto de entrenamiento.

7. **Predicciones:**
   - Utiliza el modelo entrenado para realizar predicciones sobre reviews dados por el usuario mediante un input.

## Visualización Tableau 📊
Link al Dashboard público: https://public.tableau.com/shared/C2Y56QG2T?:display_count=n&:origin=viz_share_link

![image](https://github.com/Caceres-A01706972/TC3007B_BigData/assets/83652905/3a842c85-c749-4448-9264-344a02829389)
