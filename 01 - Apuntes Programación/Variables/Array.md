# Arrays
Es un tipo de variable que nos guarda varios valores separados por comas.
Nos permite acceder a cada valor con un indice, que empieza siempre en 0.
Si queremos dirigirnos al primer elemento deberiamos poner nombreArray\[0] para dirigirnos a ese valor.

## Copiar arrays
Cuando creas un array y lo metes en una variable y en una nueva variable haces referencia a la otra, ambas estan apuntando a la misma direccion de memoria, es decir, si modificas una modificas otra.

~~~~
let number = [1,2,3,4]
let number2 = number;
number2.pop() // Eliminamos el ultimo elemento

console.log(number) // [1,2,3]
console.log(number2) //[1,2,3]
~~~~

Para copiar un array de una forma correcta hace falta hacer un .map() que si que nos crea una posicion nueva de memoria y nos permite copiar un array.



