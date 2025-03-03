# Preguntas

## 1. ¿Qué es el DOM?
El **DOM (Document Object Model)** es una interfaz que representa la estructura de un documento HTML o XML en forma de árbol. Cada elemento del documento es un nodo que puede ser manipulado mediante programación.

## 2. Relación entre el DOM y JavaScript
JavaScript usa el **DOM** para acceder y modificar dinámicamente los elementos de una página web. Esto permite actualizar contenido, cambiar estilos y manejar eventos sin recargar la página.

## 3. ¿Qué método usarías para seleccionar un elemento del DOM por su ID y cómo se utiliza?
El método `document.getElementById()` se usa para seleccionar un elemento por su **ID**:

```
let elemento = document.getElementById("miElemento");
console.log(elemento.textContent); // Muestra el contenido del elemento
```

## 4. ¿Qué método utilizarías para cambiar el color de fondo de un elemento en el DOM y cómo se implementaría?
Usando la propiedad style.backgroundColor, podemos modificar el color de fondo de un elemento:
```
let elemento = document.getElementById("miElemento");
elemento.style.backgroundColor = "blue"; // Cambia el fondo a azul
```

