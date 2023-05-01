![](https://github.com/alebusquet/PI02_Data08/blob/main/Imagenes/Henry.png)

# HENRY LABS

# PROYECTO INDIVIDUAL 02
# DATA ANALYTICS
### Alejandro Busquet

------------
# Mercado Bursátil

## Rol a desarrollar:

Simularemos una situación en donde una empresa que busca invertir en el mercado bursátil le solicita analizarlo en detalle. Considerando que la empresa no conoce esta área financiera, le solicita una explicación de qué ha sucedido en este mercado en los últimos años (considerando impactos positivos y negativos a partir del año 2000), recomendaciones de inversión (ya sea enfocada en empresas o rubros de éstas) y otra información complementaria que, usted como experto en datos, está en capacidad de brindar.

El foco del análisis es variado y amplio, siendo posible incorporar focos como la variación de precios en el tiempo, la comparación entre distintas acciones, cálculo de estadísticas bursátiles (volatilidad, promedios móviles, entre otras), recomendaciones basadas en el retorno y riesgo de inversión e incluso la creación de KPIs útiles para la toma de decisiones de inversión. La empresa deja a su disposición el o los focos que desee analizar, el resto de las exigencias se indicarán más adelante.

Considerando la cantidad de empresas existentes en el mercado bursátil, se le pide limitar el análisis a las empresas pertenecientes al índice SP500 (Standard & Poor's 500 Index).

Considerando lo anterior, el principal objetivo es poder conocer la situación del mercado bursátil en los últimos 23 años según los focos mencionados anteriormente, permitiendo que usted, como Analista de Datos, sea capaz de dar un contexto de la situación y generar recomendaciones de inversión, como mínimo se espera que pueda recomendar en qué compañías invertir y qué día de la semana es recomendable hacerlo.

## Proceso:

- **Extracción de datos (yfinance)**:
Mediante la utilización de una API, accedí a la [librería](https://pypi.org/project/yfinance/ "librería") de Yahoo Finance y procedí a extraer la información pertinente al trabajo encomendado, bajando los datos referentes al índice S&P500, los 11 índices que lo componen y las empresas pertenecientes a los tres índices de mayor crecimiento en los últimos 23 años.
También se utiliza la página oficial de [Yahoo Finance](https://finance.yahoo.com/ "Yahoo Finance").

- **Análisis Exploratorio de Datos (EDA)**:
Mediante el uso de Jupyter Notebook, se realizó  el correspondiente análisis de estadísticas descriptivas, incluyendo análisis univariado, análisis bivariado,analisis de la evolución de los precios y del volúmen, todo con el fin de comprender mejor los datos y su relación entre ellos. Todo quedó documentado en el archivo .ipynb según lo indicado.

- **Power BI**:
Una vez finalizado el trabajo en python, procedí a ingresar en la aplicación de análisis de datos Power BI, a donde llegue con los archivos .csv generados en el archivo de trabajo .ipynb

- **Dashboard**:
Procedí a la confección de dashboard interactivos, que muestran la evolución de los precios de los índices y sectores má relevantes, a fin de poder proponer una inversión fundamentada en datos históricos y utilizados para proyectar inversiones.

- **KPIs**:
Se realizaron varios KPIs a fin de clarificar la información presentada y poder ver datos de forma mas rápida y sencilla, permitiendo el abordaje de análisis y conclusiones.

- Github:
Una vez generados todos los archivos necesarios, se procedió a subir todo al repositorio, en el cual se cuenta con un detallado Readme.md que ud. está leyendo ahora.

## Reporte:

La forma de abordar la exposición consistió en partir de lo más general (el S&P500) hasta lo más puntual, que sería la propuesta de inversión. Para conocer el detalle y las conclusiones, paso a transcribir el reporte presentado:

------------
------------

¡Hola! Soy Alejandro, CEO de “Busquet Investments” y de acuerdo a lo solicitado, vengo a presentarles una propuesta de inversión bursátil, enfocada en el S&P500 desde el año 2000, y que se enfoca no desde el punto de vista técnico, sino desde el punto de vista fundamental,  a mediano y largo plazo, ya que el mercado bursátil no suele resultar la mejor opción para plazos cortos.

![](https://github.com/alebusquet/PI02_Data08/blob/main/Imagenes/Imagen%2001.png)

La intención de esta propuesta es presentar la información partiendo de lo más amplio y general, para luego abordar lo más específico y puntual.

Ante todo quiero mencionar que durante los últimos 23 años el mundo en general, y el financiero en particular, ha tenido que enfrentar varias crisis o “black swan”, como se les denomina a los hechos fuera de lo común: 

![](https://github.com/alebusquet/PI02_Data08/blob/main/Imagenes/Crisis.jpg)

Es importante conocer estos datos a priori, ya que son factores imprevistos que determinan descensos importantes en los precios del mercado, con lo que se quiere expresar que el mercado de acciones sufre alta volatilidad a lo largo del tiempo, lo que implica importantes ganancias, pero tambien pérdidas. Sin embargo, y analizando a largo plazo, se pueden extraer conclusiones que son las que quiero presentar.

El S&P500 es un índice del mercado bursátil de EEUU que representa a las 500 empresas de mayor capitalización en distintos sectores de ese mercado, teniendo actualizaciones en sus integrantes cada 3 meses.
Para información más detallada sobre el índice, su composición y actualizaciones, ver [este video](https://www.youtube.com/watch?v=z4gHjagvUWI "este video") informativo.


Para comenzar nuestro análisis, sería bueno considerar que el desempeño del S&P500 en los últimos 23 años fue del 163%, y en los últimos 5 años fue del 42%, como para tener un parámetro respecto a lo que veremos más adelante.

![](https://github.com/alebusquet/PI02_Data08/blob/main/Imagenes/Imagen%2002.png)

Con esto podemos tener una primera pauta que nos demuestra que el mercado bursátil suele recuperarse rápido ante sucesos de crisis internacional, considerando que en este último tiempo se atravesó la crisis del COVID-19, que para muchos ha sido por lejos, la peor de todas.

Sabiendo esto, pasamos ahora a analizar el índice, pero dividiéndolo en sus 11 sectores, para comenzar a desglosar un poco la información y tratar de llegar a una conclusión que resulte relevante para nuestra propuesta.

![](https://github.com/alebusquet/PI02_Data08/blob/main/Imagenes/Imagen%2003.png)

Se puede observar en el gráfico que los índices de mayor crecimiento en el período mencionado, son el de tecnología, salud y consumo.

Basándonos en este dato, propongo entonces que realicemos nuestro seguimiento con el de Tecnología (XLK), Salud (XLV) y Consumo (XLY), que en opinión de especialistas son los que están mejor posicionados para proyectar mayores crecimientos y que han demostrado ser de los que mejor atraviesan no sólo los momentos de tranquilidad, sino también los de crisis.

En los últimos 5 años, estos tres sectores demostraron crecimientos del 103%, el 77% y el 36% respectivamente, superando en conjunto el rendimiento del índice S&P 500 en mismo período.

Pasemos ahora a las siguientes preguntas: 
Por qué deberíamos invertir ahora?
Y por qué en estos 3 índices?

Bueno, en primer lugar, la pandemia de COVID-19 ha tenido un impacto significativo en la economía mundial, y muchos sectores han sufrido un retraso en su crecimiento y en el consumo. Sin embargo, el mercado bursátil ha retomado su camino alcista y a tasas similares a las anteriores al COVID.

Y por otro lado, estos tres índices han demostrado saber sobrellevar la recesión económica y han mantenido un crecimiento constante a lo largo de los años. Además factores como el aumento de la digitalización y la automatización han llevado a un mayor interés en tecnologías de la salud y bienestar, lo que sugiere que estos índices podrían continuar creciendo en el futuro.

Ahora, vamos a las 3 empresas con mejores fundamentales en cada uno de estos índices:

![](https://github.com/alebusquet/PI02_Data08/blob/main/Imagenes/Fundamentales.jpg)

![](https://github.com/alebusquet/PI02_Data08/blob/main/Imagenes/Imagen%2004.png)

![](https://github.com/alebusquet/PI02_Data08/blob/main/Imagenes/Imagen%2006.png)

![](https://github.com/alebusquet/PI02_Data08/blob/main/Imagenes/Imagen%2005.png)

Y como mencioné arriba, que la forma de abordar este análisis sería yendo de los más general a lo más específico, llegamos ahora al momento de definir la propuesta de inversión.

Esta consiste en invertir un tercio del capital en cada uno de los 3 sectores que han liderado el S&P 500 desde el año 2000, pudiendo realizarse esto mediante sus 3 índices, o mediante la inversión directa en las empresas más representativas de cada uno.
Cualquiera de las 2 opciones permite diversificar el riesgo y maximizar el potencial de ganancias. Estarán poniendo el capital en compañías que tienen un historial probado de crecimiento y que son bastante resistentes a la recesión económica, pudiendo ser una estrategia de inversión inteligente y rentable.

Antes de terminar, me gustaría señalar que la inversión en el mercado de valores conlleva ciertos riesgos y que siempre es importante hacer una investigación cuidadosa y respaldar una decisión con el asesoramiento de un asesor financiero, antes de tomar cualquier decisión final.

Sin más por decir, agradezco su atención, espero que mi presentación haya sido útil y que les haya brindado información valiosa para ayudarlos a tomar decisiones sobre sus inversiones futuras.

Muchas gracias!

------------

Autor: Alejandro Busquet<br>
Correo: algabu00@gmail.com
