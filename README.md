# BME
Aquí se encuentra el código para hacer una simulación de Monte Carlo para conocer los pesos de una cartera compuesta por n activos, de tal modo obtengamos el ratio sharp de cada una de las carteras que queramos hacer, de este modo el mayor ratio sharp define la mejor cartera encontrada para nuestros activos seleccionados. 

Los datos de los precios se descargan de yahoo finance. 

Se pueden modificar los títulos en cuestión, el número de carteras que queremos hacer y cuál es la tasa libre de riesgo, fecha de inicio de la obtención de los datos y fecha de final. Todos estos parámetros tienen valores predefinidos. Pero fácilmente modificables.
Para la tasa libre de riesgo el valor predefinido viene dado por el euribor de las 12h a 1 año cotizado en el día, y se obtiene mediante una api a una página web. 

Los gráficos que he considerado más imporantes son: distribución de los resultados diarios de los activos cotizados, un mapa de correlaciones entre los activos, y mapa de puntos con todos los ratios sharp de cada una de las carteras construidas por el model. 
