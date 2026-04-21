# Funciones en JavaScript

---

## 📌 ¿Qué es una función?

Una función es un bloque de código reutilizable que ejecuta una tarea.

---

## 🟢 Función básica

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

## 🧠 Función con retorno

function multiplicar(a, b) {
  return a * b;
}

---

## 🔥 Callback

function ejecutar(fn) {
  fn();
}

ejecutar(() => console.log("Ejecutado"));

---

## 🧠 Closures

function contador() {
  let c = 0;
  return function () {
    c++;
    return c;
  };
}

---

## 🔥 Resumen

- Las funciones reutilizan código
- Pueden recibir parámetros
- Pueden devolver valores