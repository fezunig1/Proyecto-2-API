## Proyecto-2-API
*Francisca Zúñiga*

*Data Analyst Part Time, Remote & Abril 2202*

## Descripción del proyecto

En el presente proyecto se realizó un webscraping de la página https://exchangerate.host/#/ a través de su API. 
La información que se obtiene de ésta, son los tipos de cambio de diversas monedas del mundo.

El resultado del webscraping de esta página resultó en un DataFrame de tipo de cambio en dólares de todas las monedas diponibles en una línea temporal que va desde 
enero de 2019 a la fecha (24 de mayo de 2022).

El DataFrame que resultó de este análisis fue guardado en un archivo .cvs.

## Workflow
1. Búsqueda de API con información suficiente para realizar webscraping y que fuera gratuita
2. Lectura de documentación de API y evaluar la posibilidad de implementarla en python
3. Definición de API y elección de la información a obtener
4. Creación notebook de jupyter, importar librerías e importar la información definida en el punto anterior.
5. Encontrar la información útil del jason para transformar a DataFrame
6. Obtención de información en 4 etapas (4 DataFrames), ordenándola.
7. Unión de los 4 DataFrames.
8. Creación de archivo csv (output.csv)
