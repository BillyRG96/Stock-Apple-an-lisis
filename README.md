# Stock-Apple-análisis
Análisis técnico y temporal de la accion de Apple durante cerca de 20 años.


Este docuemnto pretende demostrar una forma de analiszar el comportamiento futuro de la acción de Apple bajo un argumento que es el tiempo.

Aplicación requerida: Para la extracción de datos fue necesario utilizar Kaggle como fuente de información
Se lleva a cabo el análisis de la información con ayuda de notebook de jupyter.

Para conseguir el objetivo es necesario contar con diversos modulos de python que permiten el tratamiento de datos.

1. Numpy
2. Matplotlib
3. Pandas
4. Datetime

Y para la prediccion de valores se hizo necesario la utilización de la librería.

5. sklearn

En síntesis se pretende que el código analise en comportamiento de la accion a lo largo de los años, visualizando los diversos saltos tantos altos como bajos y determinando el momento exacto en el que ocurren estas anomalias. Para poder así determianr unos momentos exactos donde la acción podría analizarse.
Es evidente para el modelo que estas fechas podrían eventualmente analizarse como notiias de la empresa y así encontrar información relevante que nos indique lo que podría ser la razón por la que la acción se encuentra a la alza o a la baja. Ese patrón podría ofreer un indicio de lo que determina el valor de una acción a futuro. Con la busqueda de estas fechas se consigue determinar que para Apple existe unas fechas especiales en donde la empresa haces sus lanzamientos. Esto ocasiona en cierta medida el alza de la acción.


Posteriormente se encuentra un modelo predictivo que toma los valores de precio Open, High y Low, para perdecir el precio de cierre con una efectividdad bastante alta. En el mismo código se realiza el contraste entre los valores reales y las predicciones. 
