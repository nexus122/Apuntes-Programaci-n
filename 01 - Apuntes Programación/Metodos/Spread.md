# Rest - Spread
Resto o Spread son estos 3 puntitos.
Nos sirve para copiar el valor de arrays sin necesidad de que estas dos esten vinculadas, de forma que se generan espacios en memoria independientes y puedes alterarlas sin afectar a la otra.

>**...**

Aqui un ejemplo de como copiar arrays y objetos.

~~~~
// 1. Copiar un array

let gatos = ["vertin", "Bigotes"];

  

// Operador spread

// El operador ... coloca los gatos del array anterior pero sin que esten vinculados,

// y despues añadimos un elemento con , "Guit".

let mas_gatos = [...gatos, guty];

  

mas_gatos.pop();

console.log(gatos);

  

// 2. Copiar objeto

let perro = {

 nombre: 'Sultan',

 edad: 1.5,

 raza: "Mix Bodeguero"

}

  

// Funciona igual que con las arrays, copia las propiedades del perro en el nuevo objeto sin que esten vinculados.

let copia_perro = {...perro, estaVacunado: true};

copia_perro.raza = "Bodeguero Puro";

  

// El perro original conserva sus valores, pero el nuevo perro tiene los valores alterados

console.log("Perro: ", perro);

console.log("Copia perro: ", copia_perro);
~~~~

