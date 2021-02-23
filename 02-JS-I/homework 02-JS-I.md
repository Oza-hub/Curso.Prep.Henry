1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

	* Variables
	* Strings
	* Funciones (argumentos, `return`)
	* Declaraciones `if`
	* Valores booleanos (`true`, `false`)




//VARIABLES

// Variables = Se puede decir que se asemeja a un almacen de datos en el cual podemos, incluir
// varios tipos de datos como por ejemplo: Nombres, numeros, etc, a las variables hay darles un nombre
//En JS se declaran para ser usadas cuando estas sean necesarias.
//Como ejemplo se tiene:
//Asi mismo dentro de las variables existen tres tipos de ellas;  var, let, const, cosole,log.

// var= forma de declarar una variable, pero aun no es la mas usada, ademas es la forma generica para decir variable.
// let= palabra clave en la version ES6 que asigna uan variable similar a "var" pero tiene una tarea un tanto diferente.
//const= es una variable que no se puede cambiar en su valrov asignado, por demas se puede decir que almacena constantes muy similares
// a las usadas en matematicas u operaciones matematicas. 


//ejemplos:
var suma = 1 + 2;
var precio = 200;




// STRINGS
//son cadenas de texto o caracteres que se escribiran entre comillas como un texto simple o doble, 
//ejemplo:
Se tiene una cadena de cualquier material que esta compuesta de eslabones cada eslabon representa un caracter y a su un conjunto de eslabones representa una palabra o un valor como cadena de caracteres.
Ejemplo:
var marcaVehiculo = 'Chevrolet';

Al igual que otros lenguajes de programacion tambien se usan numeros reales,negativos

20
-20

Boolean

Concepto que viene de la matematica booleana, lo cual es bastante aplicado en la codigo binario de las maquinas.
Se usa en JS para significar verdadero o falso.
claramente no podemos entender facilmente estos numeros totalmente, como lo hacemos con el lenguaje natural, pero las maquinas estan diseñadas para entenderlo de esa forma.

Donde 0 es apagado = falso
Donde 1 es encendido = verdadero

La combinacion de 0 y 1 daran valores distintos

Los operadores tales +,-,*,/ como en cualquier lenguaje de programacion y estos fundamentalmente se usaran para escribir el codigo donde se requiera hacer una operacion de caracter matematico.

ejemplo
x = 1
y = 2
z = x + y
z = x - y
z = x * y
z = x / y

Claramente se entiende por parte del interprete que son la operacion suman, sustracion, multiplicacion, division.


FUNCIONES
Es una parte  importante de todo lenguaje de programacion, en JS se denomiman "callable objects". Cuando se tiene un monton de variables
se requieren de estas funciones para poder calcular nuevos valores.
La funcion siempre comienza con la palabra "function", luego viene el nombre de la funcion, parentesis y se cierra con corchetes, dentro de estos corchetes es donde se pone
Un ejemplo simple llamase una variable por ejemplo comida (desayuno),(almuerzo);(cena),(merienda).
Una alarma que indica que esta la comida lista, lo cual se podria decir que es una funcion, esta funciona es la que invocaria otro variable por ejemplo (comer).


tomo un ejemplo de Henry:
function logHola() {
	console.log('hola!');

}

ARGUMENTOS

Una variable almacena datos de entrada, ahora los valores almacenados en la variable y que son invocados se llaman argumentos.

function sumarDosNumeros(a, b) {
  var suma = a + b;
  return suma;
}

sumarDosNumeros(1, 5); // 6
aqui existe una variable que pide hacer una suma los numeros dentro de los (), seran los argumentos,porque la funcion sumarDosNumeros los esta invocando.

La declaracion return  fuerza por asi decirlo una salida de la funcion, es como si se abortara la ejecucion de la funcion.

Declaraciones if

Que pasaria "si" no vamos a la escuela
Que pasaria "si" si el carro se queda sin gasolina 
Serian ejemplo de expresiones que estan condiciones a que suceda un hecho
En este caso se devolvera un valor que puede ser falso o verdadero (true),(false).

algo como:
if (condicion) 

instruccion1;
instruccion2;







