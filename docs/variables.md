# Variables en JavaScript

---

## 📌 ¿Qué es una variable?

Una variable es un espacio en memoria donde guardamos información que puede usarse más adelante en el programa.

---

## 🟢 let

let nombre = "Juan";
nombre = "Pedro";

✔ Se puede reasignar  
✔ Tiene scope de bloque

---

## 🔵 const

const PI = 3.14;
const pais = "España";

❌ No se puede reasignar

---

## 🔴 var (antiguo)

var edad = 20;

⚠️ Problemas:
- No respeta bien el scope
- Se puede redeclarar
- No recomendado

---

## 📌 Tipos de datos en variables

let texto = "Hola";        // String
let numero = 42;           // Number
let decimal = 3.14;        // Number
let booleano = true;       // Boolean
let indefinido;            // Undefined
let nulo = null;           // Null

---

## 🧠 Scope (alcance de variables)

let global = "fuera";

if (true) {
  let local = "dentro";
  console.log(global);
  console.log(local);
}

console.log(global);
// console.log(local); // ERROR

---

## ⚡ Hoisting

console.log(a); // undefined
var a = 10;

// console.log(b); // ERROR
let b = 20;

---

## 🔥 Buenas prácticas

- Usa const por defecto
- Usa let si cambia
- Evita var

---

## 🧪 Ejemplo completo

const pais = "España";
let ciudad = "Valencia";

ciudad = "Madrid";

console.log(pais);
console.log(ciudad);

---

## 🧠 Resumen

const → no cambia  
let → cambia  
var → evitar