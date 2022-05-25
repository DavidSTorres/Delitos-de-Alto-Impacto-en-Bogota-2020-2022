# Delitos de Alto Impacto en Bogotá durante la Alcaldia de Claudia Lopez (2020-2022)

David Sebastian Torres, estudiante de Economía y Finanzas en la Universidad del Rosario
Clase de Metodos Computacionales para Politicas Publicas
Proyecto Final

<br />

<br />
<img src="https://github.com/DavidSTorres/Delitos-de-Alto-Impacto-en-Bogota-2020-2022/blob/main/Graficas/Deliots%20bogota%202018-2022.png">

## Descripción y Motivación

Actualmente la ciudad de Bogotá sufre uno de sus momentos más críticos en temas de seguridad. Según los últimos resultados presentados  de la encuesta de percepción y victimización de la Cámara de Comercio 2021) ,el 88% de los ciudadanos considera que la capital del país es insegura. Para este proyecto he decidido analizar el comportamiento de los delitos de alto impacto en Bogotá durante los últimos años, haciendo foco principal en el periodo de la Alcaldía  de Claudia López .

Las fuentes principales de los datos fueron :
   -datosabiertos.bogota.gov.co
   -datos.gov.co

Algunas cuestiones y preguntas que motivaron este proyecto:

-Bogotá cuenta con la percepción de inseguridad más alta en 6 años. Los datos de delitos reflejan esto?¿En cuánto han aumentado los delitos en Bogota?
-¿Existe estacionalidad en los delitos?¿Qué meses presentan el mayor numero de delitos en Bogotá?
-¿Qué delitos son los más comunes? ¿Y cuál localidad o zona UPZ es la más afectada?
-¿Que armas se emplean? y ¿Qué modalidad es la más común?

## Metodologia Usada

Los datos de los Delitos de Alto Impacto en Bogota estan disponibles en:
   -datosabiertos.bogota.gov.co
   -datos.gov.co

Unas vez extraído los datos los procesé, limpié y analicé con ayuda de "Pandas" y "Geopanadas"- Para la visualización de los datos utilice Tableau, en el cual creé diferentes graficas con el objetivo de responder a las preguntas planteadas.Luego, realice unos mapas  coropléticos con ayuda de "Geopandas" y QGis  para después presentar una serie de conclusiones sobre los delitos en Bogotá.

## Hallazgos

Se analizaron aproximadamente 324880 Delitos de Alto Impacto y 10 variables entre los años 2018 y 2022

Aqui algunas visualizaciones de los resultados:


<br />
Con referencia al año 2019,en el 2021 los delitos aumentaron aproximadamente 20%.Y con respecto al año 2020, en el 2021 los delitos aumentaron aproximadamente 40%.
<br />
<br />

<img src="https://github.com/DavidSTorres/Delitos-de-Alto-Impacto-en-Bogota-2020-2022/blob/main/Graficas/Tipo%20de%20delito.png">

<img src="https://github.com/DavidSTorres/Delitos-de-Alto-Impacto-en-Bogota-2020-2022/blob/main/Graficas/Delito%20%25%20total%20de%20hechos.png">
<br />
Los deltios más recurrentes fueron el Hurto a Personas y el Hurto a celulares
<br />


<img src="https://github.com/DavidSTorres/Delitos-de-Alto-Impacto-en-Bogota-2020-2022/blob/main/Graficas/Delito%20por%20mes.png">



### Hurto a personas 

<img src="https://github.com/DavidSTorres/Delitos-de-Alto-Impacto-en-Bogota-2020-2022/blob/main/Mapas/HurtoP%202020.jpg">

<img src="https://github.com/DavidSTorres/Delitos-de-Alto-Impacto-en-Bogota-2020-2022/blob/main/Mapas/HurtoP%202021.jpg">
<br />
Las localidades más afectadas fueron Engativá,Kennedy,Suba y Chapinero
<br />
<br />
<img src="https://github.com/DavidSTorres/Delitos-de-Alto-Impacto-en-Bogota-2020-2022/blob/main/Graficas/Modalidad.png">
<br />
El atraco fue la modalidad más común



