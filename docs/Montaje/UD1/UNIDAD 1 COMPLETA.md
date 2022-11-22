### 1. ¿Cómo funciona la CPU?
La CPU (O UCP, depende del idioma) está compuesta por la U.C. y la UAL, que son la unidad de control y la unidad aritmético / lógica
Al momento de ejecutar instrucciones se valen de los operadores de ambos lados. Los aritméticos son +, -, *, / y los lógicos son AND, OR y NOT

Los datos viajan entre los componentes del equipo mediante buses. Hay buses de datos, señales de control o direcciones. Los buses se clasifican en 32 y 64 bits, o x86 y 64, que son la cantidad de posiciones en 1 y 0 que pueden transportar


A nivel binario el ordenador sólo puede realizar sumas, pero en base a eso transforma el resto de operaciones a sumas y las hace igual, sin tardar más en el proceso porque es capaz de hacer miles de cálculos por segundo

### 2. Esquema
Arquitectura del ordenador → Esquema a nivel “conceptual”
Tecnología → Evolución de los materiales con los que se forman los circuitos electrónicos 

Procesador → Ejecutar instrucciones y generar señales de control para sincronizar los elementos que intervienen en sus ejecuciones

RAM → Memoria principal. Es volátil, tiene más ciclos, su velocidad de escritura es muchísimo más alta y aquí se almacenan los datos que están usando o van a usar 

10 minutos de explicación pa decir: cuantos más GHz más rápido es el procesador, porque procesa instrucciones (Que es de lo que está compuesto el programa) más rápido

El decodificador interpreta el código de la operación que hay que hacer

El secuenciador envía una serie de micro ordenes al procesador según el código de operación leído

### 3. Memorias


La información se transfiere por bloques en el sentido que marcan las flechas de los buses (De un bloque a otro si están próximos) de forma que para pasar de un lado a otro se pasa por la RAM. Un bloque de transferencia es la cantidad de información que se pasa en bloque de un nivel a otro de memoria

### 4. Bits
El ancho del bus de direcciones nos permite calcular la memoria RAM máxima (direccionable en este caso)

Windows 10 de 32 bits admite 4GB de RAM, debido a los buses de dirección que tienen los ordenadores de 32 bits

### 5. Programas
El sistema operativo es un conjunto de programas (O el programa) que permite al usuario usar el equipo sin necesidad de saber a detalle cómo funciona el hardware, ya que él mismo se ocupa automáticamente de todo lo complejo, simplificando mucho el proceso de cara al usuario

Programas de aplicación sectorial o vertical: Para un grupo de usuarios en concreto
Programas de aplicación funcional u horizontal: Para grupos más amplios, ya que permiten cierta personalización
Programas genéricos: Le sirven a muchos usuarios debido a que sus funciones son muy versátiles
Programas de desarrollo: Son para programadores y científicos de datos. Permiten crear otros programas, bases de datos, etc
Programas de ocio: Juegos o contenido multimedia

El sistema operativo está compuesto principalmente por el kernel, el shell y el entorno de escritorio (Me niego a considerarlos lo mismo)
El kernel es el núcleo del sistema, el shell es el intérprete para la terminal y el entorno de escritorio es “la skin”, la apariencia del sistema. Por norma general los entornos de escritorio tienen sus propios programas básicos (Reproductores multimedia, explorador de archivos, gestor de archivadores, etc)

El ordenador al principio sólo entendía 0 y 1, pero se han desarrollado “códigos de representación interna” que permiten almacenar valores más allá. Estaremos estudiando ASCII y UNICODE, más sus derivados (ASCII extendido y UTF-8, 16 o 32)
