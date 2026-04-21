# Funciones en JavaScript

---

## 📌 ¿Qué es una función?

Bloque de código reutilizable.

---

## 🟢 Básica

function saludar() {
  console.log("Hola");
}

---

## 🟡 Parámetros

function sumar(a, b) {
  return a + b;
}

---

## 🔵 Arrow function

const restar = (a, b) => a - b;

---

## 🧠 Retorno

function multiplicar(a, b) {
  return a * b;
}

---

## 🔥 Callbacks

function ejecutar(fn) {
  fn();
}

ejecutar(() => console.log("Hola"));

---

## 🧠 Closures

function contador() {
  let c = 0;
  return function () {
    c++;
    return c;
  };
}