# TFM_Mercadona_Tech: Fraudem


![image](https://github.com/albope/TFM_Mercadona_Tech/blob/main/src/Mercadona_Tech.png)

## Tabla de contenido

1. [Contexto del Proyecto](#contexto)
2. [Objetivo del Proyecto](#objetivo)
3. [Conjunto de datos](#datasets)
4. [Pre-requisitos](#software)
5. [Lanzar la solución](#gettingstarted)
6. [Resultados](#resultados)
7. [Agradecimientos](#agradecimientos)




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


* **Fraud**: Dataset con pedidos realizados por clientes fraudulentos.
* **Non-Fraud**: Dataset con pedidos realizados por clientes no fraudulentos.
* **Countries_iso_codes** : Códigos ISO de países.
* **Product_categories**: Categorías a las que pertenece cada producto
dentro de Mercadona Online.




## Prerequisites <a name="Prerequisites"></a>

Los prerequisitos son:

- Git
- Python3
- pip

Verificar si Python / Pip tiene la version 3 activa :snake: :

```
$> python3 --version
$> pip --version
```

----

## Getting Started <a name="gettingstarted"></a>


### **Create a virtual environment**

Si estas ejecutando la applicación en tu entorno local, es posible que desees configurar un entorno virtual con conda o venv.
```
$> conda create --name <venv_name> python=3.8

# Windows
$> activate <venv_name>

#Linux, maxOS
$> source activate <venv_name>
```


### **Installation in local host**

Clone the git repository:
```
$> git clone https://github.com/albope/TFM_Mercadona_Tech.git
$> cd TFM_Mercadona_Tech
```

Install dependencies:
```
$> pip install -r requirements.txt
```




## Resultados <a name="resultados"></a>

### Research

Despues de un trabajo de investigación repasando los algoritmos mas usados y con mejores resultados para problemas de fraude, aquí teneís los resultados de los 3 algoritmos mas usados con una variación de hyperparametros: 

[Tabla de resultados](https://github.com/albope/TFM_Mercadona_Tech/tree/main/1.Research)



### Accuracy 

|     Modelo         | % De Aciertos | Falsos Negativos |       AUC     |   Precisión   |
| ------------------ | ------------- | ---------------- | ------------- | ------------- |
| XgBoost            |    CUSTOM     |      64%         |      0.25     |               |
| RandomForest       |    CUSTOM     |      63%         |      5.00     |               |
| RegressionLogistic |    CUSTOM     |      33%         |      15.00    |               |




## Agradecimientos <a name="agradecimientos"></a> :pray:

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
