# Preguntas

1. ¿Qué es "Control Flow" (Control de Flujo)?

El **control de flujo** en JavaScript define el orden en que se ejecutan las instrucciones de un programa. Puede modificarse con estructuras como condicionales y bucles.

 **Ejemplo con `if-else`**
```javascript
let temperatura = 25;

if (temperatura > 30) {
  console.log("Hace calor.");
} else {
  console.log("El clima es agradable.");
}
```
2. ¿Qué es una "function" (Función) en JavaScript?
Una función es un bloque de código reutilizable que realiza una tarea específica.

Ejemplo de función que calcula el cuadrado de un número
```
function cuadrado(numero) {
  return numero * numero;
}

console.log(cuadrado(4)); // 16
```

3. ¿Cuántas veces se ejecutará un bucle while?
Un bucle while se ejecuta mientras la condición sea verdadera.
```
Ejemplo: Contando hasta 3

let contador = 1;

while (contador <= 3) {
  console.log("Número: " + contador);
  contador++;
}
```

4. ¿Qué método usarías para agregar un elemento al final de un array y cómo se utiliza?
Se usa el método push() para añadir elementos al final de un array.

Ejemplo con push()
```
let colores = ["rojo", "azul"];
colores.push("verde");

console.log(colores); // ["rojo", "azul", "verde"]
```
