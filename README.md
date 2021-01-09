# Detector-de-celulas-cancerigenas
##### Desarrolladores: Ayleen Contreras Solar 
<aycontreras2016@udec.cl>
      
Proyecto en desarrollo de herramienta que permitirá la detección de células cancerígenas en muestra histológicas.


El primer semestre del año 2020 se comenzó el trabajo en una herramienta capaz de detectar células cancerígenas en muestras histológicas a través de un programa desarrollado en Python 3.9.1.
Tenemos como objetivo principal, crear una red neuronal convolucional capaz de detectar una muestra e identificar si esta es cancerígena.  
Como primer paso, nos preocupamos de que nuestro programa detectara ciertas características de las células en general, para luego comenzar a pulir el programa y a futuro llegar a que detecte solo las células cancerígenas. 

El semestre 2020-2 obtuvimos como resultado la detección en células con ciertos detalles que pulir. Una vez que tengamos una buena base y claras las características que queremos que nuestro programa detecte en las muestras, incorporaremos todos estos detalles y crearemos una red neuronal que enlace cada una de estas ideas para lograr que detecte las células cancerígenas con una alta probabilidad de exactitud.


El programa  fue realizado con Python 3.9.1, usando las librerias de opencv2, numpy, pandas y matplotlib.

-**Imágenes de ejemplo que analizamos:**


- Muestra histológica 1 :


![](img_/Ejemplo1.PNG)


- Muestra histológica 2 :


![](img_/Ejemplo2.PNG)


- Probamos el programa con una imagen idela para detectar los nucleos celulares y obtuvimos el siguiente resultado:

![](img_/Ejemploideal.PNG)

- Luego pusimos a prubea con  dos imagen reales y obtuvimos los siguientes resultados:

[](img_/Ejemplodetec2.PNG)

[](img_/Ejemplodetec.PNG)

Como avance logramos hacer la deteccion de celulas donde aún falta desarrollar los algoritmo para que sean mas precisos y una vez obtenido preparar nuestra red neuronal.

