# K-Means

El K-means es un método de Clustering que separa ‘K’ grupos de objetos (Clusters) de similar varianza, minimizando un concepto conocido como inercia, que es la suma de las distancias al cuadrado de cada objeto del Cluster a un punto ‘&mu;’ conocido como Centroide (punto medio de todos los objetos del Cluster).

Para saber más sobre el K-means, ir al siguiente tutorial:

http://jarroba.com/machine-learning-python-ejemplos/

## Pseudocódigo

A continuación se muestra el Pseudocódigo del K-means:


## Prerrequisitos

El código que se encuentra en este repositorio hace uso de las librerías de numpy, matplotlib, scipy y scikit-learn. Para descargar e instalar (o actualizar a la última versión con la opción -U) estas librerías con el sistema de gestión de paquetes pip, se deben ejecutar los siguiente comandos:

```ssh
$ pip install -U numpy
$ pip install -U matplotlib
$ pip install -U scipy
$ pip install -U scikit-learn
```

## Resultados esperados de los data set

1.- DS_3Clusters_999Points.txt: Para 3 Clusters y 999 puntos, sus centroides teóricos son ((2,2),(5,5),(1,7))

2.- DS2_3Clusters_999Points.txt: Para 3 Clusters y 999 puntos, sus centroides teóricos son ((2,2),(2,4),(5,3))

3.- DS_5Clusters_10000Points.txt: Para 5 Clusters y 10000 puntos, sus centroides teóricos son ((0,0),(2,3),(4,5),(5,2),(7,5))

4.- DS_7Clusters_100000Points.txt: Para 7 Clusters y 100000 puntos, sus centroides teóricos son ((-1,3),(0,0),(0,6),(2,3),(4,5),(5,2),(7,5))

El orden de los clusters no tiene porque coincidir con los propuestos, pero los centroides si que deben de tener valores muy similares a los indicados


Para más detalles del proyecto vista la web de jarroba.com:

![alt jarroba](http://jarroba.com/wp-content/themes/jarrobav6/static/img/logojarroba.png)
