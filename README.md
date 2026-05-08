# Conceptos avanzados de JavaScript ⚡

Colección de ejercicios prácticos sobre conceptos avanzados de JavaScript asíncrono, construida con **Vite + Vanilla JS**. Cada archivo en `src/concepts/` explora un concepto diferente.

## Tecnologías

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)

## Conceptos cubiertos

| # | Archivo | Concepto |
|---|---------|----------|
| 01 | `01-environments.js` | Variables de entorno con `import.meta.env` |
| 02 | `02-callbacks.js` | Callbacks y manejo de errores con patrón Node-style |
| 03 | `03-promises.js` | Promises: `Promise.all`, `.then()`, `.catch()` |
| 04 | `04-promise-race.js` | `Promise.race` — resuelve con la promesa más rápida |
| 05 | `05-async.js` | Funciones `async` y retorno implícito de promesas |
| 06 | `06-async-await.js` | `async/await` con `try/catch` |
| 07 | `07-async-await.js` | `async/await` + `Promise.all` para ejecución paralela |
| 08 | `08-for-await.js` | Bucle `for await...of` sobre iterables de promesas |
| 09 | `09-generators.js` | Funciones generadoras (`function*`) e iteradores |
| 10 | `10-generator-async.js` | Generadores asíncronos (`async function*`) |

## Instalación y uso

```bash
git clone https://github.com/andresmdevco/js-advanced-concepts.git
cd js-advanced-concepts
npm install
npm run dev
```

Para probar cada concepto, descomenta la línea correspondiente en `src/main.js` y comenta el resto:

```js
// environmentsComponent(element);
// callbacksComponent(element);
// promiseComponent(element);
// ...
generatorAsyncComponent(element); // ← concepto activo
```

## Conceptos practicados

- Callbacks con manejo de errores al estilo Node.js
- Promises: encadenamiento, `Promise.all` y `Promise.race`
- `async/await` secuencial vs. paralelo
- Bucle `for await...of` sobre arrays de promesas
- Funciones generadoras (`function*`) y control de iteración con `yield`
- Generadores asíncronos (`async function*`)

