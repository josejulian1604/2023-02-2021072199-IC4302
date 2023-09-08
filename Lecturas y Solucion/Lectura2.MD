Jose Julian Gutierrez Badilla, carnet: 2021072199
### En que consisten los datos timeseries?
Los datos timeseries es informacion recolectada junto con la marca de tiempo en la cual fueron recolectados, como por ejemplo monitoreo de sistemas, informacion del clima, economia, etc.
### Que son metricas?
Las metricas son mediciones numericas utilizadas para monitorear o evaluar el funcionamiento de alguna aplicacion o sistema, por ejemplo estas ayudan a entender porque un sistema funciona de cierta forma.
### Explique en que consiste la Observabilidad?
La observabilidad se centra en entender lo que sucede por dentro de un sistema, de acuerdo con la informacion que produce. Esta es el proceso de entender el estado interno de un sistema y esta conformado por 3 pilares: Logs (registros en el tiempo de eventos como error log files), Metrics (representacion numerica de datos medidos en un tiempo como cantidad de logins de un usuario) y Traces (representacion de eventos en cadena en un sistema como el pedido de un cliente). La observabilidad consiste en coleccionar informacion (datos) acerca del comportamiento del sistema, y ademas interpretar esta informacion para entender el funcionamiento de todas las partes del sistema y como trabajan entre ellas
### Explique el concepto de dimensiones en datos timeseries?
Este se refiere a los diferentes atributos que se pueden utilizar para analizar los datos desde multiples perspectivas. Ademas, sirven para dar un contexto a los datos. Por ejemplo, si se necesita obtener la temperatura de un lugar en especifico, se podria obtener esta junto con el lugar en el que se registro, siendo el lugar un identificador unico que representa la dimension.
### Por que los tags en metricas permiten generar mejores graficos en Grafana?
En el caso de Grafana, las metricas son mas utiles cuando estas son recolectadas constantemente, ya que ofrece mucha variedad en como se visualizan estas metricas. Ademas, los tags son una parte esencial de Grafana ya que facilita la organizacion, y se pueden generar graficos con mas informacion y personalizados.
### Suponiendo que se estan recolectando datos IoT (Internet of Things) de miles de dispositivos, los mismos generan una metrica cada 15 segundos con el consumo de energia y temperatura, explique:

#### Por que una base de datos relacional no es una buena opcion para almacenar esta informacion?
Las bases de datos relacionales no son una buena opcion en este caso, ya que se esta recolectando volumenes sumamente grandes de datos, y estos sistemas no estan implementados para almacenar esta cantidad de datos timeseries
#### Dada la naturaleza de datos timeseries, de que forma la localidad puede ayudarnos a ahorrar dinero?
Esta informacion podria ayudar para la optimizacion de recursos, por ejemplo; si se analizan los datos timeseries de varias ubicaciones, se puede llegar a determinar en que areas los recursos se utilizan de manera ineficiente. Tambien se puede identificar en cuales areas de cierta region hay mas trafico en la red, y de esta forma aumentar los recursos (como el hardware) en las zonas que mas lo requieran, y disminuir en las que menos trafico hay.