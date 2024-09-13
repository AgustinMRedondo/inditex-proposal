Desarrollo de algorítmo de elección para Inditex (ZARA)

Con una base de datos opensource (kaggle), creamos un algorítmo (random forest classifier) un modelo para poder saber si esa prenda tendrá éxito o no

Base de datos:
La base de datos (zara.csv), esta compuesta por 270 prendas, de las cuales se segmentan (descartamos las de mujer debido a lo pequeño de la muestra) e igualamos mediante una técnica de resample para tener una muestra equitativa de las distintas prendas.

LLM:
Para añadir inteligencia artificial, a través de un LLM (librería de transformers), analizamos las descripciones de los artículos para clasificarlo en los distintos tipo de cliente de Zara (Utility, Urban, Daily)

Modelo predictivo (Randon Forest Classifier):

En la base de datos tenemos el Sales Volume (volumen de ventas), queremos averiguar si conociendo:
1. el precio
2.  posición en tienda
3.  descripción del producti
4.  si está en oferta o no
5.  si es de esta temporada
6.  que tipo de prenda es
7.  que estilo pertenece

Con estos datos averiguar si el volumen de ventas es superior a la mediana. 

Con una base de datos limitada a solo 700 filas obtenemos un modelo que predice al 91% de accuracy y 61% de poder explicativo

Utilidad del modelo:
Este modelo, se podría aplicar a todas las tiendas de Inditex, para de antemano saber si merece la pena o no enviar el producto a una determinada tienda, también a si conocer de un solo vistazo si estamos describiendo bien los artículos.
El LLM es extrapolable para analizar la eficacia de las descripciones.

Este modelo es solo un ejemplo creado por Agustín Miguel Redondo Arena, y no es válido para su uso comercial.
