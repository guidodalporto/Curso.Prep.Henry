1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. 

Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.


* `for`


Los bucles for sirven para ejecutar un código ó proceso muchas veces, realizando lo mismo y no tener que escribirlos por separado. 

Por ej. si quisiéramos que la consola nos tire un listado de números del 1 al 3, si no aplicáramos el for sería:

console.log(1);
console.log(2);
console.log(3);


El problema es si quisiéramos que se ejecute 100 veces, no terminaríamos más y sería incómodo. 


Sintaxis del for: 

for (var i =1; i<=3; i++) {

// bloque de código }



var i = 1 --> significa que el proceso arranca desde el 1

i<=3 --> Es la condición de frenado. En este caso va a finalizar cuando llegue al 3. 

i++ --> cómo se va a ir incrementando el valor. Si ponemos i++ significa que se incrementa de a 1. 





* `&&`

Simboliza el AND. Es cuando queremos combinar dos condiciones para que se cumplan a la vez.


if( 1 < 2 && 1 < 5) {

	console.log('uno es menor que dos y uno es menor que cinco);
 }



En el caso del and, y haciendo referencia a la tabla de verdad, p &&q es verdadero si los dos operadores son verdaderos. 




`||`

Simboliza el OR. Es cuando queremos que se cumpla una u otra condición.


p || q . Es falso si los dos operadores son falsos. 



 `!`

Simboliza la negación. Es como el -, invierte el operador. 


!false será true

!true será false






