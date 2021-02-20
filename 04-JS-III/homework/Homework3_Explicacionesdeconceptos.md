

# Homework: Javascript III

## Instrucciones
---
1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

	* Arrays: 


	-Son como paquetes que contiene listas de elementos, formados por distintos tipos de datos. Un ejemplo de un array puede ser la lista de un supermercado. 
	-Se definen con []
	-Un array es una colección de elementos, y que a su vez cada uno de ellos tiene un índice desde el cual se puede acceder.



	var array = ['toni', 'emi', 4, 5, 6, 'hola']
	               0       1    2  3  4

		Lo números de abajo son los índices, y empiezan a contar a partir del 0, por lo que si el array tiene 7 elementos, el último indice será 6. 

	
	Para saber la cantidad de elementos que contiene un array se puede hacer un lenght: 

	console.log(nombrearray.lenght);


	Luego de haber definido el array se podrá llamar a cualquiera de los elementos que lo contiene haciendo mención a su índice. Por ej. si quisiera que me arroje el resultado 'emi' diría: 

	array [1] y el resultado será 'emi', porque se encuentra en el índice 1. 


Si no tengo en claro la cantidad de elementos que lo contiene, y quisiera acceder al último elemento del array, podría hacer: 

array [array.lenght-1]

El array.lenght nos dará el total de los elementos, y si le restamos 1 nos dirá cuál es el último índice (porque arranca a contar a partir de 0)




