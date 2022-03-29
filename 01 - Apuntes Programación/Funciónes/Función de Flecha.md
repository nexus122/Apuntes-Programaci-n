# Funciones de flecha
## Función de flecha sin parameto
~~~~
document.addEventLisener("click", ()=>{
	console.log(' No tengo parametro pero soy una función');
})
~~~~

## Funciones con mas de un parametro
Podemos pasarle a una funcion de flecha mas de un parametro asi:
~~~~
const saludoUnaLinea = (nombre, edad) => `Soy una funcion con return y ya ${nombre} y mi edad es ${edad}`
~~~~
## Funciones de una sola linea
En una sola linea podemos devolver el procesado de la función.
~~~~
const saludoUnaLinea = nombre => `Soy una funcion con return y ya ${nombre}`
~~~~