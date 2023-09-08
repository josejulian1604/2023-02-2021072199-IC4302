Jose Julian Gutierrez Badilla

Carnet: 2021072199
### Es posible utilizar una base de datos SQL como una base de datos key-value? Como se implementaria? Comente las implicaciones de rendimiento
Si es posible utilizar una base de datos SQL como una base de datos key-value, esto ya que se puede implementar por medio de los indices, en este caso, los **keys** son los indices. Con respecto al rendimiento, esto podria ayudar mucho en caso de que se necesite acceder a informacion de manera rapida, como por ejemplo en videojuegos.

### En que consisten los datos polimorficos? Explique la razon por la cual estos son un buen caso de uso en bases de datos documentales.
Los datos son polimorficos cuando pueden ser de varios tipos o formas, y no estan restringidos a una estructura de datos fija. Estos datos son un buen caso de uso para bases de datos documentales por el hecho de que en este tipo de base de datos, los datos se almacenan en documentos, los cuales pueden tener campos que varian en su estructura y contenido.

### Presente 5 ejemplos de sistemas/casos de uso que podrian soportar consistencia eventual. Explique
Basicamente, la consistencia eventual es un modelo de base de datos que permite que los datos se propaguen a lo largo del tiempo, de modo que todos los nodos tendran una copia consistente de los datos, pero esto no sucede inmediatamente. Esto se utiliza cuando se quiere priorizar la latencia y rendimiento. Generalmente, las bases de datos key-value y wide-column se consideran eventualmente consistentes. Algunos ejemplos de sistemas que se benefician de la consistencia eventual son: 

- Redes sociales
- Sistemas de analisis de big data
- Sistemas de seguimiento de inventario en linea
- Sistemas de recomendacion
- Sistemas de geolocalizacion y mapas en tiempo real

### Por que es importante que nativamente una base de datos NoSQL implemente un REST API?
Un API REST facilita la manera en la que se interactua con la base de datos, ya que proporciona una interfaz que hace sencilla su integracion en aplicaciones y servicios externos. Ademas, se puede acceder desde cualquier lugar a traves de HTTP. Tambien el API REST permite escalabilidad, lo que permite que multiples instancias de una base de datos NoSQL puedan tener la misma API REST.

### Por que la geo localizacion de las bases de datos NoSQL pueden ayudar a mantener leyes de Data sovereignty?
Esta localizacion de las bases de datos, le permite a las empresas saber la ubicacion fisica de los datos, lo que ayuda a verificar si esto cumple con las leyes de Data Sovereignty.