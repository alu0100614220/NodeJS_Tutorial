Tutorial Node.js


Node.js is an open source, cross-platform runtime environment for server-side and networking applications. Node.js applications are written in JavaScript, and can be run within the Node.js runtime on OS X, Microsoft Windows, Linux, FreeBSD, and IBM i.

Instalación en Mac OS X Yosemite(10.10.1):

Primero: Si no tenemos un instalador de opensource, lo instalamos 

![alt tag](https://raw.githubusercontent.com/alu0100614220/NodeJS_Tutorial/master/01.png)

Segundo: Instalando el nodejs.

$ brew install node

![alt tag](https://raw.githubusercontent.com/alu0100614220/NodeJS_Tutorial/master/02.png)


Ejemplos de uso del node:

Ejemplo básico de imprimir Hola mundo.

Creamos un archivo js:

![alt tag](https://raw.githubusercontent.com/alu0100614220/NodeJS_Tutorial/master/ej1.png)

y lo ejecutamos:

![alt tag](https://raw.githubusercontent.com/alu0100614220/NodeJS_Tutorial/master/03.png)

Un ejemplo un poco más complejo:

![alt tag](https://raw.githubusercontent.com/alu0100614220/NodeJS_Tutorial/master/ej2.png)

Creamos dos funciones, la funcion decir y la funcion ejecutar.
a la funcion decir se le pasa un parametro y este es el que muestra por consola.
Hasta aqui es practicamente como el ejemplo anterior.
A la funcion ejecutar le pasamos dos parámetros, el primero de ellos es la funcion decir, no el retorno de esta, sino la funcion decir(), que pasa así a ser una variable local de la funcion ejecutar. Como segundo parametro le pasamos "hola" como valor. Al ejecutar la funcion ejecutar esta llama a algunafuncion(valor) es decir, llama a decir("hola");

![alt tag](https://raw.githubusercontent.com/alu0100614220/NodeJS_Tutorial/master/04.png)

