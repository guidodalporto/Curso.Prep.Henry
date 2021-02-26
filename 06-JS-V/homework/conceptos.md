En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. 

Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.


prototype: Todo objeto en Javascript tiene una referencia a otro objeto, llamado su prototipo (proto). 







Constructors (de Clases): Es una función que nos permite construir instancias dentro de un mismo tipo de objeto que comparten similares características, sin tener que ir definiendo uno por uno. 

Para recordarlo mejor, es como crear una plantilla para la clase del objeto que creamos. 

El auto es el objeto, y la clase es el audi, o el gol. Todos comparten las características similares. 




function Car (marca, cilindrado, color) {

	this.marca = marca;
	this.cilindrado = cilindrado;
	this.color = color; 

}


Car es el objeto, y el nombre de la constructora (función). 

var audi = new Car ('audi', 1500, 'verde');   --> voy a crear la instancia audi, que es un auto (objeto) y que tiene las caracterísricas marca: audi, cilindraro: 1500 y color verde.  

var gol = new Car ('VW', 1000, 'azul'); 

