Antonia Sofía Walker Jara

Primero que todo, dejé de lado mis tablas de la entrega 02, e hice una nueva, enfocada en el espacio digital del Servicio Nacional de Bibliotecas Públicas (SNBP).  
Quería hacer la trazabilidad de personas usuarias activas, desde 2020 hasta 2023, pero, no habían datos suficientes, por lo que, para no hacer los mismos datos que mis compañeras, me pareció llamativo ilustrar BiblioRedes.   
Conversamos con el equipo, y decidimos avanzar, considerando el espacio digital como una décimo séptima región. 

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Para poder hacer la visualización atómica, tomé las recomendaciones de Chat GPT, y lo ejecuté en Google Colab.   
Antes que nada, tuve que habilitar la lectura del lenguaje python y la ejecución de la librería Altair. Una vez realizada la lectura sin problemas, comencé a buscar formas de exportar mi csv con éxito.   
La verdad es que fue complicado, porque cuando lo subía quedaba en una carpeta de nombre “content”, y al ingresarla como ruta para encontrar mi archivo, no la podía procesar.   
Estuve alrededor de una hora viendo qué hacer, cuando atiné a subirlo nuevamente, fuera de la carpeta. De esta forma, resultó correctamente y pude ejecutar la lectura sin problemas con df.   
El mayor desafío fue lograr la visualización, ya que,ningún código lo podía ejecutar correctamente y las sugerencias de Gemini en Colab se me hacían inentendibles y poco atractivas. Resolví que la mejor forma era condensar los indicadores en un determinado año, más que observar la evolución de cada uno a través de los años, puesto que, intenté en reiteradas veces otra fórmula sin obtener resultados.   
Tras tres horas de complicaciones, logré dar con el código para tener visualizaciones anuales. Sigo creyendo que no era lo ideal, ya que me hubiese gustado hacer visualizaciones según los indicadores y su evolución a través de los años.   
Utilicé la única base de datos que hice tras la reunión que tuvimos con la Profe Trini, pensando en el nuevo curso que tomó nuestra investigación. Todos los datos son enfocados en el estado del SNBP digital.  
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Algunas preguntas que se pueden responder sobre el SNBP, en su dimensión digital, y teniendo en cuenta el csv y sus respectivas visualizaciones son: 

1. **¿Cómo fluctúa la cantidad de personas que son usuarias activas y la cantidad de inscripciones que recibe BiblioRedes cada año (desde 2019, hasta 2023)?**

   Durante 2019, hubo 79.346 inscripciones al SNBP, pero solo 75.172 fueron socios activos. 

   En el caso de 2020, hubo un alza considerable en las inscripciones al SNBP, siendo 89.403 y 86.523 usuarios activos de la plataforma. 

   2021 es el único año donde el número de socios activos supera al de inscripciones. 64.821 y 63.086, son las cifras respectivamente. 

   En 2022 se vislumbra una baja en socios activos, siendo solo 58.580, muy por debajo a los números de 2019 y el *boom* de la pandemia. En el caso de los inscritos, hay un alza con respecto a 2021, siendo 71.614.

   Por último, 2023 tiene números tibios. Los inscritos llegaron a 66.880, mientras que los usuarios activos a 64.634

   

2. **¿Cúal es la diferencia que hay entre la cantidad de capacitaciones que entrega BiblioRedes y las personas capacitadas por el sistema, cada año (desde 2019, hasta 2023)?**

   
La cantidad de capacitaciones y personas capacitadas cayó estrepitosamente con la pandemia. Cuatro años después, aún no se recupera el esplendor de 2019, con 43251 instancias de capacitación y 18784 personas capacitadas.   
En 2020, una baja a 4.291 capacitaciones y 2.166 personas capacitadas.   
2021 es el año de los números rojos. 996 instancias y solo 509 capacitados.   
En 2022, la situación se asimila a 2020, ofreciendo 5.995 capacitaciones, y alcanzando 2.889 personas capacitadas.   
Finalizando, en 2023, hubo 14.190 capacitaciones, y 7.273 egresados con éxito.   
Si bien, las cifras varían entre años, es una constante que, aproximadamente la mitad de capacitaciones es el número de personas capacitadas. 

3. **¿Cómo varía la cantidad de préstamos entre 2019, 2021 y 2023?**

   A mi parecer son los años que espejan el quiebre en la sociedad, y cómo cambió el acceso de la población chilena a las bondades del SNBP. 

   393.890 préstamos digitales recibió el SNBP durante 2019, cifra que aumentó a 461.409 en 2021, pero que, cayó a 401.250. Creo que lo más llamativo de esto es que, no cayó a lo que era la realidad de 2019, evidenciando la progresiva digitalización en la que estamos inmersos y que, seguramente, se vio acelerada tras la pandemia.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

En general, si bien las visualizaciones no son el ideal, creo que la información recabada sobre el entorno digital del SNBP es muy valiosa, y sirve para retratar varias aristas de cómo funciona el sistema, sobre todo, por los cambios estructurales que vivimos en pandemia, y como ellos se vislumbran en el acceso a la lectura de Chile, y la voluntad que hay de la población para leer.   
Creo que estos datos, entrelazados a los entregados por mis compañeras, nos pueden resultar de mucha utilidad para resolver si el acceso al SNBP y las actividades que ofrece se condicen con las proyecciones del Plan Nacional de Lectura.

   
