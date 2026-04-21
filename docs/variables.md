# Variables en JavaScript

---

## 📌 ¿Qué es una variable?

Espacio donde guardamos datos.

---

## 🟢 let

let nombre = "Juan";
nombre = "Pedro";

---

## 🔵 const

const PI = 3.14;

---

## 🔴 var (no recomendado)

var edad = 20;

---

## 📌 Tipos de datos

let texto = "Hola";
let numero = 10;
let booleano = true;
let nulo = null;

---

## 🧠 Scope

let x = 10;

if (true) {
  let x = 20;
  console.log(x);
}

console.log(x);

---

## ⚡ Hoisting

console.log(a);
var a = 5;

---

## 🔥 Buenas prácticas

- Usa const
- Usa let si cambia
- Evita var