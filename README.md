# Problematica
Al ser llamados por un cliente en el mercado de los bienes raizes con la necesidad de generar predicciones sobre propiedades y clasificarlas dependiendo de los valores dados de los datasets, se nos pidio generar un metodo de learning machine para facilitar el trabajo de clasificacion.

# Proceso de produccion
Primero se importaron los datasets con valores de entrenamiento y prueba, despues de tener esos datasets como dataframes se exploraron los valores mas importantes, haciendo una busqueda de valores faltantes y outlines para que estos no generen problemas en la clasificacion de variables, despues de generar cambios y sobre los valores de los datasets se investigo y busco el mejor metodo de Machine Learning para este tipo de casos, usamos un metodo de Regresion Logistica que en base a los valores decidimos eran los mejores para poder predecir nuestra variable dependiente.

# Elementos usados
Usamos librerias como matplotlib y seaborn para generar una gran visusalizacion sobre la poblacion y el ruido que tenian los datasets.

Librerias como pandas y numpy para obtener y modificar los datasets dependiendo las necesidades vistas durante el analisis de los datos.

Por ultimo la libreria de sklearn para traer el metodo de Regresion Logistica y generar predicciones de nuestra variable dependiente.