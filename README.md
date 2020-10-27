# TFM_Mercadona_Tech: Fraudem

## Tabla de contenido

1. [Contexto del Proyecto](#contexto)
2. [Objetivo del Proyecto](#objetivo)
3. [Conjunto de datos](#datasets)
4. [Software & librerias utilizadas](#software)
5. [Resultados](#resultados)
6. [Agradecimientos](#agradecimientos)




## Contexto del Proyecto <a name="contexto"></a>

Mercadona Tech es el canal de venta online de la compañía española de distribución Mercadona. La empresa prepara alrededor de **4000 pedidos diarios**, de los cuales algunos se pagan con tarjetas robadas. En el caso de los pedidos fraudulentos, Mercadona devuelve el dinero al cliente tras la denuncia




## Objetivo del Proyecto <a name="objetivo"></a>

Nuestro objetivo en este reto propuesto por la empresa Mercadona Tech como parte del TFM para la consecución del master en Data Analytics en EDEM era el siguiente:

**-Desarrollar un algoritmo capaz de detectar los pedidos fraudulentos en el ecommerce de Mercadona** con el fin de aportar numerosas ventajas a la empresa como:

* Reducción de costes al reducir la devolución del importe de pedidos fraudulentos

* Reducir el numero de falsos rechazos

* Reducir el número de pedidos incorrectos aumentando así la tasa de autorización de pagos
 
 
 
 
Este repo contiene los diferentes scripts que hemos utilizado en las distintas fases de la implementación de este proyecto de Machine learning:

* Scripts utilizados en la ingesta de los datos
 
* Scripts utilizados en la fase de tratamiento de los datos
 
* Scripts utilizados en la fase de desarrollo e implementación del modelo utilizado
 



## Conjunto de Datos <a name="datasets"></a>

Los datos proporcionados por la empresa Mercadona Tech se dividian en 4 datasets diferentes y provenian de pedidos realizados en su ecommerce durante un periodo de 2 años y medio y ascendian a un total de mas de 10 millones de registros:


* **COCO Dataset**: Dataset abierto que contiene más de 220k imágenes etiquetadas y 1.5 millón de clases de objetos diferentes.
* **Ego Hand Dataset**: Dataset creado por la Universidad de Indiana que contiene 15,083 manos etiquetadas y 48 videos diferentes de manos.
* **OID Dataset** : Dataset con 500 clases de objetos diferentes.
* **Medical Mask Dataset**: Dataset creado para una competición de Kaggle con 682 imagenes de gente portando mascarillas médicas.




## Software & librerias utilizadas <a name="software"></a>

* [LabelImg](https://github.com/tzutalin/labelImg) : Software de etiquetado de Imagenes [[link]]
* [OpenCV](https://github.com/opencv/opencv) : Biblioteca de Visión Artificial
* **Tensor Flow** : Biblioteca de Machine Learning
* **Keras** : Biblioteca de Redes Neuronales
* **Dlib** : Biblioteca de algortimos de Machine Learning




## Resultados <a name="resultados"></a>

### Accuracy 

| First Header  |    DATASET    |       mAP     |       FPS     | 
| ------------- | ------------- | ------------- | ------------- |
| RetinaNet     |    CUSTOM     |      64%      |      0.25     |
| YOLOv3        |    CUSTOM     |      63%      |      5.00     |
| Tiny YOLO     |    CUSTOM     |      33%      |      15.00    |




## Agradecimientos <a name="agradecimientos"></a>

* A nuestras familias por hacernos más fácil el desarrollo del proyecto
* A nuestros tutores por su ayuda a la hora de dirigir el alcance y conseguir los objetivos del proyecto
* A Edem por su atención en los momentos académicos de más incertidumbre de  este atípico 2020
* A nuestros compañeros y profesores por su disposición sobre como afrontar las cuestiones del proyecto



## Authors
- Alberto Bort
- Salim Chikh
- Maria Miravet
- Marta Arcos
- German Valera
