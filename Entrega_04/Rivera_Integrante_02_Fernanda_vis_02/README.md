Para esta entrega tuve utilicé las mismos datos que recopilé para la entrega 02, sobre el Servicio Nacional de Bibliotecas Públicas (SNBP). Pero corregí lo que estuvo mal en la anterior, junté los datos que tenía en solo un archivo y me fije que el csv estuviera delimitado por comas. 

Luego comencé a trabajar en un notebook de Google Collab, primero con el archivo “SNBP_2023_database” para donde quería hacer una comparación de la cantidad de servicios de bibliotecas del SNBP por región. Aquí se responden las preguntas ¿Qué región tiene más bibliotecas? o ¿Es equitativo el acceso a la lectura en el territorio?. Con esa misma tabla se pueden crear más visualizaciones que respondan ¿En qué región hay más usuarios? o ¿en qué región se realizan más préstamos? Para ello considero importante considerar la población de cada región, aspecto que incluí en la breve crónica que acompaña la visualización. 

Sé que considerar solo el año 2023 es muy poco, pero no existen datos de años anteriores en los informes respecto a la cantidad por región. Me basé en las bibliotecas que salen en la [página](https://www.bibliotecaspublicas.gob.cl/buscar-biblioteca) contando manualmente por región.

Luego con el Con el archivo “SNBP_2021_2022_2023_database” hice una visualización que muestra la cantidad de servicios del SNBP por cada año, muestra cómo han ido aumentando. Se responde la pregunta ¿Han aumentado los servicios del SNBP?

Finalmente, el archivo “Préstamos_2021_2022_2023_database” tiene los préstamos realizados por región en cada año. La visualización con barras horizontales representa aquello. Se responde la pregunta ¿Aumentan los préstamos que hacen las personas en bibliotecas públicas con el pasar del tiempo?

Todas las visualizaciones fueron realizadas en un notebook de Google Colab usando las librerías de Altair el archivo se llama Altair.ipynb. 
