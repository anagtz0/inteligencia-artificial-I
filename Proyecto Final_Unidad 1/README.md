## P1.1 Regresión

### Análisis de Factores Asociados a los Homicidios en México

Este proyecto analiza la relación entre distintos factores socioeconómicos y demográficos y la cantidad de homicidios registrados en las 32 entidades federativas de México.

A partir de datos oficiales del INEGI, se construyó una base de datos consolidada para explorar cómo variables como desempleo, ingreso, densidad poblacional, educación y composición demográfica podrían estar asociadas con el número de defunciones por homicidio.

En el proyecto se crean 2 modelos de regresión lineal con la finalidad de ver cuál tiene mejor desempeño, evaluando parámetros como R cuadrada ajustada, probabilidad del estadístico f, MSE, entre otros. 

Las bases de datos originales se pueden encontrar en la página oficial del INEGI.

Se utilizaron las siguientes bases de datos que contienen la siguiente información:

* "[Homicidios.csv](https://www.inegi.org.mx/app/tabulados/interactivos/?pxq=Mortalidad_Mortalidad_08_733c4167-e790-42a9-8bc7-f290480f41af)" (2024)
    * **Estado** -> Nombre de las 32 entidades federativas.
    * **DefuncionPorHomicidio** -> Cantidad de defunciones por causa de homicidio en cada estado.


* "[Desocupacion.csv](https://www.inegi.org.mx/app/tabulados/default.html?nc=624)" (2024) (*estos datos venían por trimestre, por lo que se obtuvo el promedio de los 4 trimestres para tener un sólo dato*)
    * **Estado** -> Nombre de las 32 entidades federativas.
    * **TasaDesocupacion** -> Porcentaje de personas sin ocupación laboral con respecto a la Población Económicamente Activa (PEA).


* "[DensidadPoblacional.csv](https://en.www.inegi.org.mx/app/tabulados/interactivos/?pxq=Poblacion_Poblacion_07_fb7d5132-39f0-4a6c-b6f6-4cbe440e048d)" (2020)
    * **Estado** -> Nombre de las 32 entidades federativas.
    * **DensidadPoblacional** -> Habitantes por kilómetro cuadrado.


* "[Educación.csv](https://www.inegi.org.mx/app/tabulados/interactivos/?pxq=Educacion_Educacion_13_c457f93a-1497-43b9-8c16-962c4cf3af40)" (ciclo escolar 2024/2025)    
    * **Estado** -> Nombre de las 32 entidades federativas.
    * **EsperanzaEscolaridad** -> Cantidad de años que se espera que una persona entre 5 y 29 años esté inscrita en algún nivel educativo.


* "[Ingreso.csv](https://www.inegi.org.mx/app/tabulados/interactivos/?pxq=Hogares_Hogares_11_861f5732-c3db-4614-be03-741f649d605c)" (2024) (*estos datos venían por trimestre, por lo que se multiplicó por 4 para obtener el valor anual*)
    * **Estado** -> Nombre de las 32 entidades federativas.
    * **IngresoTotal** -> Ingreso anual en pesos mexicanos.


* "[CantidadDeJovenes.csv](https://www.inegi.org.mx/app/tabulados/interactivos/?pxq=Poblacion_Poblacion_01_e60cd8cf-927f-4b94-823e-972457a12d4b)" (2020)
    * **Estado** -> Nombre de las 32 entidades federativas.
    * **15a19anios** -> Cantidad de jóvenes entre 15 y 19 años.


* "[HombresvsMujeres.csv](https://www.inegi.org.mx/app/tabulados/interactivos/?pxq=Poblacion_Poblacion_02_be8efe6d-504a-4d9e-8848-6b578542061b&idrt=123&opc=t)" (2020)
    * **Estado** -> Nombre de las 32 entidades federativas.
    * **HombresvsMujeres** -> Cantidad de hombres por cada 100 mujeres.

  Este proyecto incluye los siguientes documentos:
- [Reporte en formato ipynb](./P%20P1.%20623201.ipynb)
- [Reporte en formato html](./P%20P1.%20623201.html)
- [Base de datos Defunción por Homicidio](./Homicidios.csv)
- [Base de datos Desocupación](./Desocupacion.csv)
- [Base de datos Densidad Poblacional](./DensidadPoblacional.csv)
- [Base de datos Esperanza de Escolaridad](./Educacion.csv)
- [Base de datos Ingreso promedio](./Ingreso.csv)
- [Base de datos Cantidad de Jóvenes entre 15 y 19 años](./CantidadDeJovenes.csv)
- [Base de datos Relación Hombres vs Mujeres](./HombresVsMujeres.csv)
