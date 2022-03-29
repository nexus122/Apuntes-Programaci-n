# Funciones de callback
Son las funciones a las que llamas cuando una función a acabado, para ejecutar una nueva función que procese los datos y no moleste al flujo normal de ejecución.

En este ejemplo vemos como se llama a una api y cuando ha cargado los datos llama a la funcion de callback, que nos muestra la información por pantalla.

~~~~
async function obtenerChiste(cb){
	let response = await fetch('etc...');
	let chiste = await response.json()
	cb(chiste.value);
}

function updateDOM(joke){
	jokeDiv.textContent = joke.
}
~~~~

Las funciones de callback son muy comunes en programación asincrona y hay que entenderlas bien.