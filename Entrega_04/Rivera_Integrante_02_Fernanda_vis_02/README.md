## Entrega 04 - Visualizaciones - Fernanda Rivera Robledo
Para esta entrega utilicé las mismos datos que recopilé para la entrega 02, sobre el Servicio Nacional de Bibliotecas Públicas (SNBP). Pero corregí lo que estuvo mal en la anterior, junté los datos que tenía en solo un archivo y me fije que el csv estuviera delimitado por comas. 

Para hacer las visualizaciones atómicas habilité la lectura del lenguaje python y la ejecución de la librería Altair
en el notebook de Google Colab e importé mis archivos csv. Una vez comprobado que se leían bien, comencé a probar con los gráficos que sugería la Gemini. Pero también le fui pidiendo que me mostrara cómo hacer las visualizaciones que yo quería. 

Comencé con el archivo “SNBP_2023_database” donde quería hacer una comparación de la cantidad de servicios de bibliotecas del SNBP por región. Aquí se responden las preguntas:
1. **¿Qué región tiene más bibliotecas?**

Pregunta que puede parecer obvia, pero me resulta importante tener una visualización en nuestro proyecto que represente aquello. Las regiones con más bibliotecas son: Región Metropolitana (89), Región de la Araucanía (51), Valparaíso (36) y Los Lagos (32). Puede que exista una relación respecto a la cantidad de habitantes, pero en el caso de la región de la Araucanía que a 2023 tenía 1.028.201	habitantes en comparación a la región del Biobío que tenía 1.681.430 y cuenta sólo con 28 bibliotecas. 
   
2. **¿Es equitativo el acceso a la lectura en el territorio?**

Las bibliotecas se concentran en las regiones antes mencionadas. Las regiones con menos bibliotecas son: Región de Arica y Parinacota (7), Región de Magallanes (7) y Región de Tarapacá (7). Mientras que otras superan las 25 bibliotecas por región. 

Con esa misma tabla de “SNBP_2023_database” se pueden crear más visualizaciones que respondan **¿En qué región hay más usuarios?** o **¿En qué región se realizan más préstamos?** Para ello también me parece importante considerar la población de cada región, aspecto que incluí en la breve crónica que acompaña la visualización. 

Sé que considerar solo el año 2023 es muy poco, pero no existen datos de años anteriores en los informes respecto a la cantidad por región. Me basé en las bibliotecas que salen en la [página](https://www.bibliotecaspublicas.gob.cl/buscar-biblioteca) contando manualmente por región.

Luego con el con el archivo “SNBP_2021_2022_2023_database” hice una visualización que muestra la cantidad de servicios del SNBP por cada año, muestra cómo han ido aumentando. Se responde la pregunta:
- **¿Han aumentado los servicios del SNBP?**
Sí, han ido en aumento, pasando de cubirir un 95% del territorio nacional a cubirir un 97%. Si se puede ver que disminuyeron los puntos de bibliometro de 39 en 2021 a 33 en 2023 y las bibliotecas regionales. Pero, aumentaron los demás items (bibliotecas en convenio y programas inclisivos de acceso a la lectura). 

Finalmente, el archivo “Préstamos_2021_2022_2023_database” tiene los préstamos realizados por región en cada año. La visualización con barras horizontales representa aquello. Para esta visualización tuve bastantes problemas para que se mostraran las tres variables, los años, las regiones y las cifras. Utilicé Gemini ára lograrlo. Con la visualización se responde la pregunta:
- **¿Aumentan los préstamos que hacen las personas en bibliotecas públicas con el pasar del tiempo?**

Sí, va aumentando. Aquí considero relevante tomar en cuenta el contexto de pandemia en 2021 que pudo influir en que no se hayan hecho tantos préstamos de libros. Que en la mayoría de las regiones de 2021 a 2022 los préstamos se duplicaron.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Todas las visualizaciones fueron realizadas en un notebook de Google Colab usando las librerías de Altair el código está en el archivo llamado Altair.ipynb
