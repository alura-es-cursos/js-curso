# Resolución del desafío 2

Saber cómo usar funciones es uno de los conceptos fundamentales en la programación y el desarrollo de software. Las funciones desempeñan un papel crucial en la organización, modularización y reutilización del código.

Con eso en mente, hemos creado una lista de actividades (opcionales) centradas en la práctica para mejorar aún más tu experiencia de aprendizaje.

**Sugestión de respuestas**
1. Crear una función que muestra "¡Hola, mundo!" en la consola.

```javascript
function mostrarHola() {
  console.log("¡Hola, mundo!");
}

mostrarHola();
```
2. Crear una función que recibe un nombre como parámetro y muestra "¡Hola, [nombre]!" en la consola.

```javascript
function mostrarHolaNombre(nombre) {
  console.log(`¡Hola, ${nombre}!`);
}

mostrarHolaNombre("Alice");
```
3. Crear una función que recibe un número como parámetro y devuelve el doble de ese número.

```javascript
function calcularDoble(numero) {
  return numero * 2;
}

let resultadoDoble = calcularDoble(5);
console.log(resultadoDoble);
```
4. Crear una función que recibe tres números como parámetros y devuelve su promedio.

```javascript
function calcularPromedio(a, b, c) {
  return (a + b + c) / 3;
}

let promedio = calcularPromedio(4, 7, 10);
console.log(promedio);
```
5. Crear una función que recibe dos números como parámetros y devuelve el mayor de ellos.

```javascript
function encontrarMayor(a, b) {
  return a > b ? a : b;
}

let numeroMayor = encontrarMayor(15, 9);
console.log(numeroMayor);
```
6. Crear una función que recibe un número como parámetro y devuelve el resultado de multiplicar ese número por sí mismo.

```javascript
function cuadrado(numero) {
  return numero * numero;
}

let resultado = cuadrado(2);
console.log(resultado);
```
