# Resolución del desafío 1

Saber cómo usar funciones es uno de los conceptos fundamentales en la programación y el desarrollo de software. Las funciones desempeñan un papel crucial en la organización, modularización y reutilización del código.

Con eso en mente, hemos creado una lista de actividades (opcionales) centradas en la práctica para mejorar aún más tu experiencia de aprendizaje.

**Sugestión de respuestas**

2.Cambia el contenido de la etiqueta `h1` con `document.querySelector` y asigna el siguiente texto: `Hora del Desafío`.

```javascript
let titulo = document.querySelector('h1');
titulo.innerHTML = 'Hora del Desafío';
```

3.Crea una función que muestre en la consola el mensaje `El botón fue clicado` siempre que se presione el botón `Console`.

En el `index.html` , agregamos en el `onclick` el siguiente código:

```javascript
<button onclick="mostarMensajeEnLaConsola()" class="button">Console</button>
```

En el `app.js`

```js
function mostarMensajeEnLaConsola() {
    console.log('El botón fue clicado!')
}
```

4.Crea una función que se ejecute cuando se haga clic en el botón "`prompt`", preguntando el nombre de una ciudad de Brasil. Luego, muestra una alerta con el mensaje concatenando la respuesta con el texto: "`Estuve en {ciudad} y me acordé de ti`".

En el `index.html` , agregamos en el `onclick` el siguiente código:

```javascript
<button onclick="mostarAlerta()" class="button">Alert</button>
```

En el `app.js`

```js
function mostarAlerta(){
     let ciudad = prompt("Por favor, ingresa el nombre de una ciudad de Brasil:");
    alert("Estuve en " + ciudad + " y me acordé de ti.");
} 
```

5.Crea una función que muestre una alerta con el mensaje: "Amo JS" siempre que se presione el botón "Alerta".

En el `index.html` , agregamos en el `onclick` el siguiente código:

```js
<button onclick="mostarAlerta()" class="button">Alert</button>
```

En el `app.js`

```js
function mostarAlerta(){
    alert("AMO JS");
} 
```

6.Al hacer clic en el botón "suma", pide 2 números y muestra el resultado de la suma en una alerta.

En el `index.html` , agregamos en el `onclick` el siguiente código:

```js
 <button onclick="sumaDosNumeros()" class="button">Suma</button>
```

En el `app.js`

```js
function sumaDosNumeros(){
    let primerNumero = parseInt(prompt('Digite el primer numero'));
    let segunNumero = parseInt(prompt('Digite el segundo numero'));
    let resultado = primerNumero + segunNumero;
    alert('${primerNumero} + ${segunNumero} = ${resultado}')
}
```

