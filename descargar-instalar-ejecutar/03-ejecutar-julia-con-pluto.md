# Ejecutar un cuaderno con Pluto

## 1. Abrir la consola de Julia

Abrí una terminal y ejecutá:
```
julia
```

## 2. Iniciar Pluto

Cuando veas el texto `julia>`, escribí lo siguiente y presioná Enter:
```julia
import Pluto; Pluto.run()
```
Pluto abrirá automáticamente una pestaña en tu navegador predeterminado.

## 3. Abrir un cuaderno

En la pantalla de inicio de Pluto verás un campo de texto **"Open a notebook"**. Tenés varias formas de usarlo:

### Sugerencias automáticas

Al empezar a escribir una ruta, Pluto te sugiere archivos `.jl` que encuentra en tus carpetas. Podés navegar por las sugerencias con las teclas de flecha y seleccionar con Enter.

### Pegar la ruta del archivo

Podés copiar la ruta completa de un archivo desde el explorador de archivos y pegarla directamente en el campo. Por ejemplo:
```
C:\Users\tu_usuario\...\unidades-tematicas\unidad-tematica-1\U01-N01.jl
```

### Pegar un enlace de internet

Si el cuaderno está publicado en línea (por ejemplo en GitHub), podés pegar la URL directamente y Pluto lo descargará y abrirá.

---

Una vez ingresada la ruta o el enlace, hacé clic en **"Open"** y el cuaderno se cargará en el navegador.

> **Nota:** la primera vez que abrís un cuaderno, Pluto necesita descargar y compilar todos los paquetes que usa. Esto puede llevar varios minutos. Las celdas mostrarán un símbolo de carga (es normal, no se rompió nada). Las veces siguientes el proceso es mucho más rápido.

## 4. Verificar que todo funciona

Para confirmar que la instalación está completa y en orden, abrí el cuaderno de prueba de este repositorio. Está disponible en la carpeta `descargar-instalar-ejecutar/` con el nombre `cuaderno-de-prueba.jl`. Podés abrirlo pegando su ruta en el campo **"Open a notebook"** de Pluto, o usando el enlace directo desde GitHub siguiendo los pasos del archivo [04-descargar-cuadernos-desde-github.md](04-descargar-cuadernos-desde-github.md).

Si el cuaderno carga y se ve correctamente, la instalación está lista.

## 5. Cerrar Pluto

Volvé a la terminal y presioná `Ctrl+C`, o simplemente cerrá la ventana de la terminal.
