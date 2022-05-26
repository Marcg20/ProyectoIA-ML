# Proyecto final IA

## Integrantes:
1. Catalina Ortegón
2. Mariana Cortés

## Introducción del proyecto
Para este proyecto se desea determinar la potabilidad del agua, por lo cual se utilizó un dataset que contiene nueve caracteristicas las cuales son las siguientes:
1. pH: pH del agua (0 a 14).
2. Dureza: Capacidad del agua para precipitar el jabón en mg/L.
3. Sólidos: Sólidos totales disueltos en ppm.
4. Cloraminas: Cantidad de cloraminas en ppm.
5. Sulfatos: Cantidad de Sulfatos disueltos en mg/L.
6. Conductividad: Conductividad eléctrica del agua en μS/cm.
7. Carbono orgánico: Cantidad de carbono orgánico en ppm.
8. Trihalometanos: Cantidad de trihalometanos en μg/L.
9. Turbidez: Medida de la propiedad de emisión de luz del agua en NTU.

Para la etiqueta de potabilidad 1 representa que es potable y 0 que no es potable. 

El dataset tiene entonces 3271 filas × 10 columnas y el link es el siguiente: https://www.kaggle.com/datasets/adityakadiwal/water-potability

## Desarrollo
Para resolver este problema se usaron 4 métodos, K-nearest neighbors, Support vector machine, Decision Tree y Multi-layer Perceptron classifier, los cuales se evaluaron con dos métricas, MCC y F1 score, finalmente se eligió Multi-layer Perceptron classifier al tener mayor porcentaje en las métricas de evaluación.

## Resultados
Los datos de la tabla corresponden a los resultados de las métricas usando el 10% de los datos del dataset que se destinó para evaluar. 

<img src="https://github.com/Marcg20/ProyectoIA-ML/blob/main/re.png" width="250"/>


## Conclusiones
* El dataset utilizado no presenta buenos datos en las características entonces no permite determinar adecuadamente la potabilidad del agua. Al observar en la parte de discusión de Kaggle se observa que la mayoría de los comentarios hablan sobre las anormalidades de los datos.
* El mejor resultado según las métricas usadas es MLP, seguido de SVM, KNN Y por último Decision Tree. 

## Link del video
https://youtu.be/6NiK2HO5oto
