Aquí voy a explicar cosas que ha usado el profe sin que estuviera en el temario, para los más curiosos

## Usar `echo` para crear un archivo
Para entender ésto es necesario saber que la terminal tiene operadores, con los cuáles pueden realizarse ciertas (valga la redundancia) operaciones, con instrucciones, archivos, etc, etc

El operador que ha usado para hacer éso es la redirección, que se hace con `>`. Sirve para guardar la salida de un comando en un archivo en vez de mostrarla y su sintaxis es la siguiente:
> `comando > archivo`

Siendo `comando` el comando a ejecutar y `archivo` la ruta al archivo en el que quieras guardar la salida. El uso más común es usar `echo` como comando porque es el que da la salida que quieras. Ejemplo: `echo "He hecho éste archivo probando la redirección" > prueba.txt`