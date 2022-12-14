## Programa que calcula el desnivel entre dos puntos referidos a una superficie

Autores de Proyecto:
Avalos Rocha Andrea Jiménez Vargas Mariel del Rosario
Uribe García Leonardo Miguel


Institución:
Facultad de Ingeniería Civil, Universidad de Colima, Campus Coquimatlán


Carrera:
Ingeniero Topógrafo Geomático


Grado y gruPo:
3ºB


Profesor titular:
Sebastián González Zepeda


Lugar:
Campus Coquimatlán; Coquimatlán, Colima


Fecha:
03 de diciembre de 2022

![image](https://user-images.githubusercontent.com/119511140/205765509-8f4d2708-450f-4530-9938-25ae3a2fd269.png)

## **Porgrama que calcula el desnivel entre dos puntos referidos a una superficie**

Andrea Avalos Rocha (1), Mariel del Rosario Jiménez Vargas (2), Leonardo Miguel Uribe García (3)

(1) Facultad de Ingeniería Civil, 1604, Colima-Coquimatlán Kilómetro 9, Jardines del Llano, 28400, Coquimatlán, Col. (1)20186380,aavalos9@ucol.mx, (2) 20186524 mjimenez@ucol.mx (3) 20186673 luribe0@ucol.mx
 
## **Resumen**

Se generará un programa en colab el cual tiene como propósito leer un archivo de Excel, en el que se encuentran datos de una nivelación previamente realizada del campus Coquimatlán en la Facultad de Ingeniería Civil, para obtener como resultado que el programa genere de manera automática el desnivel obtenido, también para un mayor entendimiento visual graficar los resultados. 
Palabras clave: Programa, Nivelación y Desniveles.

# **Abstrac**
A program will be generated in colab whose purpose is to read an Excel file, in which there is data from a previously carried out leveling of the Coquimatlán campus in the Faculty of Civil Engineering, to obtain as a result that the program automatically generates the unevenness obtained, also for a better visual understanding graph the results.
Keywords: Program, Leveling and Slopes.


## **1.	Introducción**

En el presente reporte se habla acerca de la obtención de desniveles, llevado a cabo a través de una nivelación previamente realizada con los datos necesarios para su desarrollo. Con la finalidad de generar un programa en Colab que nos arroje de manera automática los resultados del desnivel del terreno.  Para entrar en conceptualización, cuando hablamos de desnivel, hacemos referencia a la diferencia de altura entre dos o más puntos. El desnivel también se puede definir como la diferencia de elevación o cota entre ambos puntos.
Dentro de este reporte se mencionan diversos apartados, tales como objetivo general, objetivos específicos, estado del arte; en el que se incluye marco histórico, marco conceptual, marco teórico, marco metodológico y marco de referencia, así mismo, se mencionan las herramientas a utilizar, la metodología empleada, resultados, conclusiones y finalmente, la bibliografía, todos los mencionados con la finalidad de que tanto como el reporte como el trabajo realizado en campo, sea elaborado de la mejor manera.
La realización de este proyecto principalmente, tiene como propósito generar un programa que ayude a respaldar a las personas enfocadas al campo de la topografía, ya que este programa ayudará a ahorrar tiempo al momento de realizar cálculos de este tipo. De igual forma, el desarrollo de este proyecto permite aplicar los conocimientos adquiridos en la materia de Proyecto Integrador, así como la de Topografía General II.
Dicho todo esto, daremos inicio al reporte comenzando con el objetivo general de este proyecto.

 
## **2.	Desarrollo**

Materiales
Para poder llevar a cabo este proyecto, se hizo uso de los siguientes materiales:
•	Computadora con acceso a Internet
•	Google Colab (Google Colaboratory)
•	Excel
•	Datos obtenidos de una nivelación 

Primeramente, se pasan los archivos obtenidos de una nivelación topográfica de campo a un archivo Excel.

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-007.png](https://i.postimg.cc/mZpFP9ND/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-007.png)](https://postimg.cc/8sWC3jYQ)
Figura 1. Datos de nivelación a Excel

En seguida de ello, se guarda el archivo en su equipo. Se recomienda que este sea guardado en formato .cvs o .xlsx.  

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-008.png](https://i.postimg.cc/HkrGTqWn/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-008.png)](https://postimg.cc/v4w2zSVw)

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-009.png](https://i.postimg.cc/nzZw9gxv/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-009.png)](https://postimg.cc/v1qvpPcB) 
Figuras 2 y 3. Guardar en formato cvs o xlsx

Una vez teniendo estos, se exportan a Google Drive. De tal manera que se guardó en la carpeta especial de Google Colab para así facilitar los procesos de búsqueda del archivo al momento de querer abrirlo en Colab.

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-010.png](https://i.postimg.cc/rwrhnMF1/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-010.png)](https://postimg.cc/hXKbhFmv)
Figuras 4. Archivo en Google Drive

Una vez teniendo nuestro archivo Excel en Google Drive con los datos de la nivelación, se comienza a programar en Colab de tal manera que abra y lea los archivos de Excel. Para ello, se emplearon comandos como “from google.colab import drive”, “from google.colab import data_table” y “import xlrd”.

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-011.png](https://i.postimg.cc/Kj171D1P/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-011.png)](https://postimg.cc/q6d6YnXq)
Figura 5. Comandos para abrir y leer el dataframe

Con el código hecho hasta ese momento nos debe de mostrar la tabla.

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-012.png](https://i.postimg.cc/DfRpqS7v/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-012.png)](https://postimg.cc/4nb1GNKq)
Figura 6. Tabla mostrada

Una vez ya leído y mostrado la tabla, se obtiene la suma de las columnas de lecturas positivas (‘Lect(+)’) y de lecturas negativas (‘Lect(-)’), lo cual, para poder obtener estas primeramente se accede a las columnas específicas que se desea hacer la operación del dataframe.

Luego de ello aplicamos el comando sum() a cada una de las columnas a las que accedimos. Este comando calcula la suma de todos los elementos de un array sobre el eje especificado.

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-013.png](https://i.postimg.cc/xjNtT9MW/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-013.png)](https://postimg.cc/9zVGL5xp)
Figura 7. Suma de columnas

De esta manera obtenemos la suma de la columna de lecturas positivas y la columna de lecturas negativas.

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-014.png](https://i.postimg.cc/KvNLmWq6/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-014.png)](https://postimg.cc/9rDzpLjb)
Figura 8. Resultados de la suma

Una vez teniendo el resultado de la suma de cada columna, so obtiene el desnivel, el cual simplemente se realiza una resta de las lecturas positivas con las lecturas negativas.

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-016.png](https://i.postimg.cc/ZKV9Gd0Z/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-016.png)](https://postimg.cc/xcNTHqKF)
Figura 9. Desnivel de las lecturas

Con el comando print(), se muestra el desnivel.

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-017.png](https://i.postimg.cc/T3sKwvr4/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-017.png)](https://postimg.cc/VJjfGTZq)
Figura 10. Resultado del desnivel


Ahora bien, con todo lo anterior ya hecho, se realiza la gráfica de cómo es la diferencia de desnivel en dicho terreno. Para ello se hace empleo de librería matplotlib.

Primeramente, se definió los valores del dataframe (archivo Excel) que se desean graficar. En este caso, las cotas y los P.V. En toda nivelación, para poder graficar y mostrar el perfil de cómo es la pendiente durante todo un tramo del terreno, se debe de establecer las cotas y los puntos que poseen dichas cotas.

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-018.png](https://i.postimg.cc/ZnjRzGbj/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-018.png)](https://postimg.cc/ctgZQ588)
Figura 11. Definiendo valores para graficar

Luego de ello, se especifica cual irá en el eje X y eje Y. En el eje X irá los P.V y en el eje Y las cotas.

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-019.png](https://i.postimg.cc/bJyffsZc/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-019.png)](https://postimg.cc/p966DVQq)
Figura 12. Proceso de graficación del desnivel

De esta manera se obtiene una representación gráfica de cómo es el desnivel de los datos de la nivelación.

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-020.png](https://i.postimg.cc/6q8SBRwS/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-020.png)](https://postimg.cc/9wj1pDDt)
Figura 13. Representación gráfica del desnivel

Ahora bien, se utilizó la condición If para determinar si la pendiente del desnivel es creciente, decreciente o si el terreno es plano.

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-021.png](https://i.postimg.cc/G3fVqMx1/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-021.png)](https://postimg.cc/nMv3LGWd)
Figura 14. Introducción de la condición If

Con las condiciones establecidas, cuando se ejecuta el programa se imprime que la pendiente es decreciente, pues el desnivel que hubo es menor a 0 (-2.873).

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-022.png](https://i.postimg.cc/W4sHhxT0/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-022.png)](https://postimg.cc/rDYJHndp)
Figura 15. Uso de la condición If

Ahora bien, luego se usó el módulo time,  math, geopy y seaborn para poder obtener la ubicación en tiempo real con sus coordenadas de dónde se realizó la nivelación topográfica.

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-023.png](https://i.postimg.cc/5NLJvddr/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-023.png)](https://postimg.cc/yk124GNh)
Figura 16. Código para especificar el lugar

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-024.png](https://i.postimg.cc/zXCmvCTZ/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-024.png)](https://postimg.cc/mtgp6Fd8)
Figura 17. Especificación del lugar

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-025.png](https://i.postimg.cc/Z5bQq1Tp/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-025.png)](https://postimg.cc/0b4nWXKy)
Figura 18. Datos de la ubicación

Finalmente se usó el módulo basemap para mostrar un mapa de escala global en donde marca en que parte del mundo se encuentra realizada la nivelación topográfica.

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-026.png](https://i.postimg.cc/3r2fFKN2/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-026.png)](https://postimg.cc/Dmyc23qz)
Figura 19. Uso de basemap

Y así el código nos muestra lo siguiente:

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-027.png](https://i.postimg.cc/Bv8ML3RL/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-027.png)](https://postimg.cc/QB3pw28h)
Figura 20. Mapa

## **3. Manejo de datos**

Por parte de los datos que se emplearon se encuentran toda la información de Excel obtenida de una nivelación topográfica, en donde se ordenaron por Punto Visado (P.V), Lecturas Positivas (Lect (+)), Lecturas Negativas (Lect (-)), Altura del instrumento (A.I.) y Cotas.

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-028.png](https://i.postimg.cc/KjbNHMjB/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-028.png)](https://postimg.cc/ph0z9yDL)
Figura 21. Datos de Nivelación Topográfica

Ahora bien, por parte de los datos para programar, se emplearon librerías y módulos tales como pandas, numpy, xrld y matplotlib, en donde:

Pandas: Nos ayudó en el manejo y análisis de estructuras de datos. Con ella pudimos manipular nuestros datos del dataframe (Excel) para poder calcular lo esperado, así como poder trabajar con los datos a manera de tabla.

Numpy: Nos ayudó en el cálculo de operaciones matemáticas de nuestros datos a partir de arreglos o matrices. Cabe destacar que con esta librería nos permitió usar funciones con las cuales pudimos ejecutar operaciones aritméticas.

Xrld: Nos permitió analizar y trabajar con datos de archivos Excel a manera de tablas.

Matplotlib: Esta librería nos permitió crear y personalizar gráficos a partir de los datos que se tienen de nuestro archivo Excel

From google.colab import drive: Este código nos permitió accede a Google Drive para así poder abrir la información que guardamos en nuestra nube y poder usarla en Google Colab, en este caso, nuestro archivo Excel.

Seaborn: Aunque sea una biblioteca similar a Matplotlib, esta nos sirvió para poder graficar a detalles datos e información geoespacial.

Time: Este módulo nos sirvió para trabajar con información geoespacial a escalar actual.

Math: Este módulo nos proporcionó acceso a las funciones matemáticas definidas por el estándar C.
Basemap: No sirvió para poder proyectar mapas 

Como recomendación, sugerimos que al utilizar el programa realizado por nosotros se debe de tener antes muy bien ordenada la información de nuestro dataframe (Excel) pues solo se podrá ejecutar de la manera correcta si se cuenta con la información ordenada en columnas y cada una de ellas con los nombres correspondientes (P.V, Lect(+), A.I., Lect (-) y cotas).

Cabe destacar que es importante tener instalado la librería basemap con pip install pues si esta no está instalada, el programa nos marcará error.

[![Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-029.png](https://i.postimg.cc/fTBK8kNS/Aspose-Words-8dd2f1f8-59c2-44ba-9aa4-0c278bdba44f-029.png)](https://postimg.cc/xcNMCfq9)
Figura 22. Basemap instalado

Importante mencionar que en el archivo Excel xlsx vienen 3 hojas con diferentes nivelaciones. En la primera hoja el desnivel es 0, por lo tanto el terreno es plano. En la segunda hoja, el desnivel es  negativo, por lo tanto la pendiente es decreciente. En la última hoja, el desnivel es positivo y por ello la pendiente es creciente.

![image](https://user-images.githubusercontent.com/119511140/206040581-a794915e-2ec3-4dc3-806f-d731d12c5234.png)
![image](https://user-images.githubusercontent.com/119511140/206040603-cdef3ee7-4866-4701-b331-90c9cb429147.png)

Figura 23 y 24. Hoja1 Excel, terreno plano

![image](https://user-images.githubusercontent.com/119511140/206040706-1c9c1804-af19-4d1d-b089-89eb5d2d1fc9.png)
![image](https://user-images.githubusercontent.com/119511140/206040720-5a9993e5-c46b-4e5d-a997-acb5b9adfed5.png)

Figura 25 y 26. Hoja2 Excel, pendiente decreciente

![image](https://user-images.githubusercontent.com/119511140/206040819-26ff515d-6c9d-46ca-8812-82fccc11107e.png)
![image](https://user-images.githubusercontent.com/119511140/206040845-72654ff9-2150-406f-8af1-34a7a9c69f0f.png)

Figuras 27 y 28. Hoja3 Excel, pendiente creciente

## **4. Resultados**

Respecto a los resultados, podemos decir que, si se cumplieron con los objetivos establecidos en nuestro proyecto, es decir, se pudo programar y se obtuvo el desnivel que hay entre dos bancos de nivel al igual que también se logró representar el desnivel a manera de una gráfica de barras, en donde se especifica a detalle como es el comportamiento de los datos en cada estación o punto visado. Así mismo, el código elaborado muestra el lugar, las coordenadas y un mapa con la zona donde se realizó la nivelación.

De igual manera, con el desarrollo de este proyecto se pudo comprobar que la nivelación realizada en campo fue realizada correctamente, pues con el análisis de los datos obtenidos a la hora de programar pudimos colaborar nuestras hipótesis sobre cómo es el desnivel que existe desde un banco de nivel a otro.

El código realizado fue el siguiente:

#Universidad de Colima- Facultad de Ingeniería Civil

#Carrera: Ingeniero Topógrafo Geomático

#Elaborado por: Avalos Rocha Andrea, Jiménez Vargas Mariel del Rosario y Uribe García Leonardo Miguel

#Grado y grupo: 3°B

#Programación de computadoras II

%matplotlib inline

from google.colab import drive

from google.colab import data_table

from vega_datasets import data

import pandas as pd

import numpy as np

import xlrd

import matplotlib.pyplot as plt

from matplotlib.ticker import PercentFormatter

import seaborn as sb

from mpl_toolkits.basemap.test import Basemap

from geopy.geocoders import Nominatim

import time

import math


print('--Programa que calcula el desnivel entre dos puntos referidos a una superficie--')

print('Bienvenido a nuestro programa, este te ayudará a conocer el desnivel de una nivelación topográfica y te mostrára de forma gráfica como es esta')

print('IMPORTANTE: Para que el programa te funcione debes tener tu información en Excel separada con columnas y cada columna con los nombres: P.V, Lect(+),  (A.I), Lect(-) y Cotas')

print('P.V significa Punto Visado')

print('A.I significa Altura del instrumento')


data_table.enable_dataframe_formatter()

data.airports()

drive.mount('/gdrive')

df= pd.read_excel('/gdrive/MyDrive/Colab Notebooks/Proyecto_Integrador/Nivelación.xlsx', sheet_name = "Hoja2")

print(df.head())


columna_lectpostivas = df['Lect(+)']

sumlecturaspositivas= sum(columna_lectpostivas)

print('La suma de las lecturas positivas es: ', sumlecturaspositivas)


columna_lectnegativas = df['Lect(-)']

sumlecturasnegativas= sum(columna_lectnegativas)

print('La suma de las lecturas negativas es: ', sumlecturasnegativas)


desnivel= sumlecturaspositivas-sumlecturasnegativas

print('El desnivel de esta nivelación es: ', desnivel)


valores= df[['P.V','Cota']]

ax= valores.plot(x='P.V',y='Cota',rot= 0)

plt.xlabel("P.V")

plt.ylabel("Cota")

plt.title("Nivelación Geométrica- Perfil del tramo")

plt.show()


if desnivel > 0:

  print('La pendiente va de forma creciente')
  
if desnivel < 0:

  print('La pendiente va de forma decreciente')
  
if desnivel == 0:

  print('No hay pendiente, el terreno es plano')
  

geolocator = Nominatim(user_agent="AppMap")

lugar= input("Lugar donde se hizo la nivelación: ")

location = geolocator.geocode(lugar)

print(location)

print((location.latitude, location.longitude))

geo = Nominatim(user_agent="AppMap", timeout=2)

zona = geo.geocode(lugar)

plt.figure(figsize=(16,12))

my_map=Basemap(projection="robin", lon_0=0,lat_0=0)

my_map.drawcoastlines()

my_map.drawcountries()

my_map.fillcontinents(color='green')

x,y = my_map(zona.longitude,zona.latitude)

my_map.plot(x,y,color='red', marker="o",markersize="15")

plt.title("Ubicación donde se hizo la nivelación")


Link del código en colab:
https://colab.research.google.com/drive/1C6E2Dd3u2N2XMu5XNNS4_6UzthRyFEGr?usp=sharing

![image](https://user-images.githubusercontent.com/119511140/205766049-bdad725a-d933-48c8-883f-50879eea5b4b.png)
![image](https://user-images.githubusercontent.com/119511140/205766168-d43b3795-980f-4b23-8a7f-44ba2f6e3755.png)
![image](https://user-images.githubusercontent.com/119511140/205766245-1b1544d7-2670-48a7-b6f6-1c608bf8607f.png)
![imagen](https://user-images.githubusercontent.com/119511140/205765358-4d456bd6-f9b1-42a0-9142-dc9660b3c1b6.png)
![image](https://user-images.githubusercontent.com/119511140/205765378-25cafb26-2ad8-4ca2-a3d6-d863ffe019f1.png)


## **5. Conclusiones**

A manera de conclusión, podemos decir que nuestro proyecto concluyó de la manera en que esperábamos, el código que desarrollamos aplicado al campo de la Topografía y Geomática funciona, arrojándonos el valor del desnivel entre dos bancos de nivel. De igual forma, el código nos muestra información geoespacial, la cual es muy importante en la ingeniería debido a que los datos geoespaciales ayudan a describir eventos con ciertas características con una ubicación en la superficie terrestre, por lo general, estos datos geoespaciales combinan información de ubicación (en este caso coordenadas del lugar donde se realizó la nivelación) e información que posee las características del evento que se realizó. 

Consideramos que la programación podría llegar a ser muy útil y necesaria en nuestra vida laboral como futuros ingenieros, ya que este es un gran tutor cuando se trata de aprender a solucionar problemas, principalmente situaciones de lógica e ingenio. Es el arte de crear soluciones desde cero a paradigmas complejos a base de un pensamiento estructurado, lógico y creativo. 

Por ello, no cabe duda alguna que la programación juega un papel muy útil en la vida humana, y en las ingenierías no es la excepción, pues con ella podemos realizar varios procesos u operaciones las cuales manualmente nos tomaría bastante tiempo realizarlas, por lo que con el uso de programas informáticos podemos efectuar y ejecutar procesos de manera más rápida, precisa y eficaz, tal y como lo pudimos demostrar en este proyecto, pues a hacer uso de lenguajes informáticos de programación, pudimos facilitar operaciones y procesos con los que tardamos más y nos ayudó a ahorrarnos mucho tiempo de trabajo.

Para finalizar, el realizar este código nos deja una gran enseñanza, pues ejemplifica cómo es que podemos emplear la programación o los lenguajes de programación para resolver cuestiones de la vida diaria de cualquier tipo, principalmente enfocados en la vida estudiantil, aplicando los conocimientos adquiridos durante el curso de Programación de Computadoras II.



## **6. Referencias**
 
Aws(2022).”¿Qué es Python?, Amazon.com. Recuperado el 31 de octubre de 2022, de https://aws.amazon.com/es/what-is/python/

Brinker, W. (1997). Topografía. Ed. Alfaomega. 9ª Edición. Colombia.

Cientec instrumentos. (2022). ¿Cómo usar un Nivel Topográfico? 01 de septiembre de 2022, de Cientec instrumentos Sitio web: https://cientecinstrumentos.cl/como-usar-un-nivel-topografico/

Gabri,P(17 de octubre de 2018). ArcGeek, recuperado de https://acolita.com/evolucion-de-las-tecnicas-topograficas/

Torres N., Villate B. (2001). Topografía. Ed. Escuela Colombiana de Ingeniería. 4a edición. Colombia
