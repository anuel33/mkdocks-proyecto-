# Arrays en JavaScript

---

## 📌 ¿Qué es un array?

Un array es una lista de elementos.

---

## 🟢 Crear array

let numeros = [1, 2, 3, 4];

---

## 🟡 Acceder

numeros[0];

---

## 🔥 Métodos principales

numeros.push(5);
numeros.pop();
numeros.shift();
numeros.unshift(0);

---

## 🧠 Recorrer array

numeros.forEach(n => console.log(n));

---

## 🔵 map

let doble = numeros.map(n => n * 2);

---

## 🟣 filter

let mayores = numeros.filter(n => n > 2);

---

## 🔥 reduce

let suma = numeros.reduce((a, b) => a + b);

---

## 🧠 Resumen

Los arrays sirven para almacenar listas de datos