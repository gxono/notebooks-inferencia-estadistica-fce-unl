# Preguntas frecuentes

## El cuaderno tarda mucho en cargar o parece que no hace nada

Es normal. La primera vez que abrís un cuaderno, Pluto descarga e instala todos los paquetes que ese cuaderno necesita. Dependiendo de tu conexión y tu computadora, puede tardar entre dos y diez minutos. Las celdas mostrarán un ícono de carga mientras trabaja — no cerrés el navegador ni la terminal.

Una vez instalados, los paquetes quedan guardados en tu computadora. La próxima vez que abras el mismo cuaderno — o cualquier otro que use los mismos paquetes — no necesitará descargar nada y el proceso será notablemente más rápido.

---

## Julia no se reconoce como comando en la terminal

Esto suele pasar cuando Julia no quedó agregada al PATH durante la instalación.

**Si instalaste desde la Microsoft Store:** reiniciá la terminal e intentá de nuevo. La Store agrega Julia al PATH automáticamente, pero la terminal necesita reiniciarse para verlo.

**Si instalaste desde la página oficial:** durante la instalación en Windows debía aparecer la opción **"Add Julia to PATH"**. Si no la marcaste, la solución más sencilla es desinstalar y volver a instalar marcando esa opción.

---

## Pluto no abre el navegador automáticamente

En algunas configuraciones Pluto no logra abrir el navegador solo. En ese caso, mirá la terminal: debería aparecer una línea como:

```
Go to http://localhost:1234/?secret=xxxx in your browser
```

Copiá esa dirección y pegala manualmente en tu navegador.

---

## Cerré el navegador por accidente. ¿Perdí el trabajo?

No. Pluto guarda los cambios automáticamente en el archivo `.jl`. Mientras la terminal con Julia siga abierta, podés volver a abrir el navegador, ir a `http://localhost:1234` y retomar desde donde estabas.
