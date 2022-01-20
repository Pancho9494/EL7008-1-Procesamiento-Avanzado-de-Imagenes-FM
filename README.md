# EL7008-1 Procesamiento Avanzado de Imágenes

Estudiante: Francisco Molina

Este repositorio almacena las tareas correspondientes al curso EL7008-1 de primavera 2021.

## Tarea 1 - Pirámides de Gauss y Laplace

Esta tarea tiene por objetivo implementar el cálculo de las pirámides de Gauss y Laplace de una misma imagen para luego reconstruir dicha imagen a partir de las pirámides.

El siguiente ejemplo muestra el funcionamiento del sistema implementado:


La imagen original:

<img src="Tarea_1-Piramides_de_Gauss_y_Laplace/cuadro.jpg" alt="Imagen original" width="256" height="200"/>

La pirámide de Gauss:

<img src="Tarea_1-Piramides_de_Gauss_y_Laplace/piramideGauss.png" alt="Pirámide de Gauss" width="1509" height="200"/>

La pirámide de Laplace:

<img src="Tarea_1-Piramides_de_Gauss_y_Laplace/piramideLaplace.png" alt="Pirámide de Laplace" width="1509" height="200"/>

La imágen original y la reconstruida en escala de grises:

<img src="Tarea_1-Piramides_de_Gauss_y_Laplace/ogVSrec.png" alt="Original vs reconstrucción" width="512" height="200"/>

El informe detallando la implementación se encuentra en [Tarea 1](Tarea_1-Piramides_de_Gauss_y_Laplace/Tarea_1.pdf)


## Tarea_2-Reconocimiento_de_objetos

Esta tarea tiene por objetivo implementar el calculo de puntos de interés mediante el método de Harris y la implementación de un detector de objetos que utilize los puntos de interés de Harris o descriptores SIFT, usando RANSAC.

El siguiente ejemplo muestra el funcionamiento del sistema implementado:

La imagen original con sus puntos de interés detectados mediante Harris:

<img src="Tarea_2-Reconocimiento_de_objetos/puntosInteres.png" alt="Detección de puntos de interés de Harris" width="320" height="250"/>

El match de los puntos de interés entre la imagen original y la de búsqueda, mediante RANSAC:

<img src="Tarea_2-Reconocimiento_de_objetos/matching.png" alt="Matching de puntos de interés con RANSAC" width="480" height="250"/>

La detección final del objeto:

<img src="Tarea_2-Reconocimiento_de_objetos/deteccion.png" alt="Detección del objeto" width="320" height="250"/>

El informe detallando la implementación se encuentra en [Tarea 2](Tarea_2-Reconocimiento_de_objetos/Tarea_2_EL7008.pdf)


## Tarea 3 - Clasificación de edad usando características tipo HOG

Esta tarea tiene por objetivo diseñar e implementar un sistema de claisifación de edad basado en características HOG, utilizando como clasificadores SVM y Random Forest.

El mejor clasificador obtenido fue una **SVM** que logra una **accuracy de 0.71 sobre el conjunto de validación**, a continuación se presentan las métricas correspondientes a este clasificador:

<img src="Tarea_3-Clasificacion_de_edad_usando_caracteristicas_tipo_HOG/metricas.png" alt="Metricas clasificador SVM" width="309" height="121"/>

Y a continuación se presenta la matriz de confusión de dicho clasificador:

<img src="Tarea_3-Clasificacion_de_edad_usando_caracteristicas_tipo_HOG/CM.png" alt="Matriz de confusión SVM" width="304" height="228"/>

El informe detallando la implementación se encuentra en [Tarea 3](Tarea_3-Clasificacion_de_edad_usando_caracteristicas_tipo_HOG/Tarea_3_EL7008.pdf)


## Tarea 4 - Clasificación de edad usando LBP y redes neuronales

Al igual que en la tarea anterior, esta tiene por objetivo diseñar e implementar un sistema de clasificación de edad, pero basado en características tipo histogramas LBP y utilizando redes neuronales como clasificador.

En la siguiente figura se muestra un ejemplo del cálculo del histograma LBP en una imagen:

<img src="Tarea_4-Clasificacion_de_edad_usando_LBP_y_redes_neuronales/LBP.png" alt = "Histograma LBP sobre imagen" width="428" height="221"/>

El mejor clasificador obtenido fue una **Red neuronal** con una capa oculta de 64 neuronas, que logra una **accuracy de 0.66 sobre el conjunto de validación**, a continuación se presenta la curva de pérdidas de este clasificador en la que se puede apreciar el mecanismo de *early stopping* implementado:

<img src="Tarea_4-Clasificacion_de_edad_usando_LBP_y_redes_neuronales/perdida.png" alt = "Curva de pérdida CE" width="574" height="298"/>

Y a continuación se presenta la matriz de confusión normalizada de dicho clasificador:

<img src="Tarea_4-Clasificacion_de_edad_usando_LBP_y_redes_neuronales/CM.png" alt="Matriz de confusión NN" width="304" height="228"/>

El informe detallando la implementación se encuentra en [Tarea 4](Tarea_4-Clasificacion_de_edad_usando_LBP_y_redes_neuronales/Tarea_4_EL7008.pdf)


## Tarea 5 - Redes neuronales convolucionales para clasificar edad






<details> 
  <summary>Token </summary>
   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
</details>

