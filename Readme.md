<p align='center'>
<img src ="https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png">
<p>

<h1 align='center'>
 <b>PROYECTO INDIVIDUAL Nº2</b>
</h1>
 
# <h1 align="center">**`Mercado bursátil`**</h1>

### Rol a desarrollar

Como actividad, se nos planteó una situación en donde una empresa nos solicitaba analizar el mercado bursatil en detalle, con la intención de invertir en el mismo. Cumpliendo con el rol de un experto en datos, debíamos considerar que la empresa no conocía área financiera, por lo tanto era necesario realizar una explicación de qué ha sucedido en este mercado en los últimos años, considerando impactos positivos y negativos a partir del año 2000. Todo esto sumado a recomendaciones de inversión, ya sea enfocada en empresas o rubros de éstas. 

Se nos dió libertad para elegir el foco del análisis ya que el mismo es variado y amplio, siendo posible incorporar focos como la variación de precios en el tiempo, la comparación entre distintas acciones, cálculo de estadísticas bursátiles (volatilidad, promedios móviles, entre otras), recomendaciones basadas en el retorno y riesgo de inversión e incluso la creación de KPIs útiles para la toma de decisiones de inversión.

Considerando la cantidad de empresas existentes en el mercado bursátil, se nos solicitó limitar el análisis a las empresas pertenecientes al índice SP500 ([Standard & Poor's 500 Index](https://www.google.com/url?q=https://en.wikipedia.org/wiki/List_of_S%2526P_500_companies&sa=D&source=docs&ust=1676566032938438&usg=AOvVaw3J6gZYtEH8xJABTCf0pYqO)).

El principal objetivo era poder conocer la situación del mercado bursátil en los últimos 23 años y en base a esto, ser capaz de dar un contexto de la situación y generar recomendaciones de inversión.

### Desarrollo de las actividades 

Inicialmente mendiante un proceso de ETL se elaboró un archivo que contiene los nombres de las empresas pertenecientes al índice SP500.
A travéz del sitio web de finanzas sugerido (Yahoo Finance), se procedió a extraer la información correspondiente a los registros de los movimientos de los precios de las acciones de las empresas objetivo, desde el año 2000 hasta la actualidad.

Se llevó a cabo un análisis exploratorio de los datos mediante el cual se detectaron y trataron datos faltantes, duplicados y outliers.
Finalmente se decidió encarar el análisis en profundidad a través del cálculo de distintos indicadores financieros tales como la volatilidad y la tasa de retorno diario.
Este último fué calculado en base al Adj Close, el cual refleja el precio de cierre real, ajustado por cualquier evento corporativo que pueda afectar el precio de la acción, como dividendos, desdoblamientos de acciones o fusiones de empresas. Dichos indicadores pertimitieron realizar una comparativa entre los distintos sectores de empresas que componen el SP500, y de ese modo poder elegir aquellos con mayor tasa de retorno por acción y menor volatilidad, lo cual se traduce en mayores ganancias y estabilidad a través del tiempo. Juntos hacen a un menor riesgo de inversión. 

Por último se eligió la herramienta de visualización PowerBi, en la cual se elaboró un dashboard disponible en el repositorio, con la finalidad de condensar la información obtenida de una manera más gráfica y accsesible. 




