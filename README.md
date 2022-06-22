# Desafío 3 - Funciones

En este desafío validaremos nuestros conocimientos en transformación y modificación de funciones y códigos en función de instrucciones dadas.

Lee todo el documento antes de comenzar el desarrollo individual, para asegurarte de tener el máximo de puntaje y enfocar bien los esfuerzos.

## Descripción

Aplicando los conceptos y herramientas aprendidas hasta ahora desarrolla el siguiente desafío que consiste en un conjunto de ejercicios que nos permitirán poner en práctica los elementos clave de la unidad.

## Requerimientos

__1.__ Transforma esta declaración de función a una función de expresión. El ejercicio debe quedar en un archivo nombrado `1 funcion.js` __(1 Punto)__

```js
function example(a, b, c){
  return a+b+c
}

```

__2.__ Transforma las siguiente función a una arrow function de una línea. Este ejercicio debe quedar en un archivo llamado `2 arrow.js` __(1 Punto)__

```js
suma = function(a, b){
  return a + b
}
```

__3.__ Se tiene como base el siguiente ejercicio que cambia el color de un elemento de HTML al hacerle click __(Total: 3 Puntos)__

```html
<div id="ele1"> hello </div>
<script>
function pintar(){
  ele = document.getElementById("ele1")
  ele.style.backgroundColor = 'yellow'
}

ele = document.getElementById("ele1")
ele.addEventListener("click", pintar);
</script>
```

__3.1.__ Modifica la función para que reciba el elemento clickeado de forma de no tener que seleccionarlo nuevamente dentro de la función (__1 Punto__). Para obtener el puntaje debes entregar el 3 pintar.html válido funcionando en conjunto con el código modificado.

💡 __Tip:__ revisa en la guía las funciones anónimas

__3.2.__ Modifica el código anterior para poder pasarle un color como argumento a la función pintar. El color debe ser verde (green) por defecto, al hacer clic en el párrafo se debe pasar amarillo como color. (__1 Punto__).

__3.3.__ Separa el código en 2 archivos: 3 pintar.html y script.js. El script js debe estar dentro de la carpeta assets/js (__1 Punto__). Para obtener el puntaje debes entregar los archivos cumplimiento la estructura pedida en conjunto con los requerimientos de 3.1 y 3.2

__4.__ Construye una página web con las siguientes características (__Total: 5 puntos__)

● Crea 4 divs que tengan alto y ancho de 200px y de distintos colores de fondo usando el atributo style. Cada uno de los divs debe tener un identificador único.

● Crea un script que guarde dentro de una variable global un color dependiendo de la letra del teclado presionada. (__2 Puntos__).

○ Al presionar la letra __a__ un color a tu elección.<br>
○ Al presionar la letra __s__ un segundo color a tu elección.<br>
○ Al presionar la letra __d__ un tercer color al presionar la letra d.<br>
○ Para guardar el color revisa el tip al final del enunciado.

● Dentro del script agrega el evento que al hacerle click a uno de los divs, este cambie de color al color seleccionado. Utiliza addEventListener para agregar el evento. (__3 Puntos__)

💡 __Tip:__ El siguiente script te ayudará a realizar acciones en función de que se presione una tecla

```js
document.addEventListener('keydown', function (event) {
  if (event.key === 'a') {
    /* Cambiar a color 1 */
  } else if (event.key === 's') {
    /* Cambiar a color 2 */
  }
})
```

😊 ¡Mucho éxito!

## Solución

[Try site](https://felipe-m-dev.github.io/JS-Challenge-03/)
