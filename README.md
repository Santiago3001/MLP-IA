OBJETIVOS
Implementar el algoritmo MLP.

Evaluar la precisión (MSE, error de entrenamiento y validación) de una MLP teniendo en cuenta distintas
configuraciones: cantidad de capas, cantidad de neuronas, funciones de activación.

Elaborar un informe completo en base a las pruebas realizadas.

PROBLEMÁTICA
Este trabajo consiste en implementar el algoritmo MLP que permita dado un dataset, parametrizar la cantidad de capas, neuronas y 
funciones de activación con los que se entrenará la red neuronal. La idea es desarrollar una aplicación que defina la arquitectura de la red 
(con 3 salidas, cada una asociada a un patrón de entrada), tome los datos de diferentes datasets, entrene el modelo y devuelva los resultados 
de clasificación (MSE, error de entrenamiento y validación). La implementación deberá contar también con una interfaz de usuario para el
ingreso de un patrón distorsionado (determinado por el usuario), que será clasificado según alguno de los patrones aprendidos, mostrando 
los resultados obtenidos. Los patrones a detectar y clasificar estarán contenidos en una matriz de 10x10 que contendrán las letras d, b, f 
como se ve en las siguientes figuras:

![Figura](imágen/letras.png)

En la carpeta output se encuentra el ejecutable ventana.exe disponible apra windows 10/11 donde se podrá entrenar, inferir y obetenr la rpecision del modelo
Tambien se encuentra un instructivo del programa
