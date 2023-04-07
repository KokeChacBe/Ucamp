# Ucamp
# Predicción de calificación de aplicaciones en Play Store

Este proyecto tiene como objetivo predecir la calificación de las aplicaciones en la Play Store utilizando diferentes técnicas de aprendizaje automático.

El conjunto de datos utilizado en este proyecto es un conjunto de datos de la Play Store que contiene información sobre las aplicaciones, como su nombre, categoría, tamaño, precio, etc. La variable objetivo es la calificación, que se encuentra en una escala de 0 a 5.

El proyecto utiliza Python y las siguientes bibliotecas: Pandas, NumPy, Scikit-learn, Seaborn y Matplotlib.

El proyecto se divide en las siguientes partes:

Importación de las bibliotecas necesarias y del conjunto de datos.
Limpieza de los datos y preparación para el modelado.
Entrenamiento de un modelo de regresión lineal.
Evaluación del modelo utilizando la métrica de error cuadrático medio y coeficiente de determinación.
Visualización de los resultados mediante gráficas.
Ensamble y ajustes.
El modelo de regresión lineal se entrena y se evalúa utilizando la división de los datos en entrenamiento y prueba. También se realizan visualizaciones para analizar la distribución de los errores y comparar los valores reales con los valores predichos.

Para mejorar la precisión del modelo, se utiliza la técnica de ensamblaje de Random Forest, junto con el ajuste de hiperparámetros para encontrar los valores óptimos de los parámetros del modelo.

El resultado final es un modelo preciso que puede predecir la calificación de las aplicaciones en la Play Store.
