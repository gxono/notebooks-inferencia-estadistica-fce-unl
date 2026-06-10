# Descargar cuadernos desde GitHub

Los cuadernos de este repositorio están disponibles en GitHub y podés usarlos de tres formas: pegando el enlace directamente en Pluto, descargando solo el archivo que necesitás, o descargando el repositorio completo.

---

## Opción 1: abrir el cuaderno directamente desde GitHub (sin descargar)

Pluto permite abrir cuadernos desde una URL. Para eso necesitás el enlace al archivo **en formato raw**.

1. En GitHub, navegá hasta el archivo `.jl` que querés abrir.
2. Hacé clic en el botón **"Raw"** (arriba a la derecha del contenido del archivo).
3. Copiá la URL de la barra del navegador — va a empezar con `raw.githubusercontent.com`.
4. Abrí Pluto, pegá esa URL en el campo **"Open a notebook"** y hacé clic en **"Open"**.

Pluto descargará el cuaderno automáticamente y lo abrirá. Tené en cuenta que los cambios que hagas **no se van a guardar en GitHub** — se guardarán en un archivo temporal en tu computadora.

---

## Opción 2: descargar un cuaderno individual

Si solo necesitás un cuaderno:

1. En GitHub, navegá hasta el archivo `.jl` que querés descargar.
2. Hacé clic en el ícono de descarga (una flecha apuntando hacia abajo, arriba a la derecha del contenido).
3. El archivo se guardará en tu carpeta de descargas. Movelo a donde prefieras y abrilo desde Pluto.

---

## Opción 3: descargar el repositorio completo

Si querés tener todos los cuadernos guardados en tu computadora:

1. En la página principal del repositorio en GitHub, hacé clic en el botón verde **"Code"**.
2. Seleccioná **"Download ZIP"**.
3. Descomprimí el archivo en la carpeta que prefieras.
4. Abrí Pluto y navegá hasta el archivo `.jl` que querés usar (ver [03-ejecutar-julia-con-pluto.md](03-ejecutar-julia-con-pluto.md)).

Esta opción es la más conveniente si vas a trabajar con varios cuadernos o si no tenés conexión a internet.

> **Atención:** si un cuaderno se actualiza en GitHub después de que lo descargaste (Opción 2 u Opción 3), tu copia local **no se actualizará automáticamente**. Para tener la versión más reciente tenés que volver a descargarlo. Si usás la Opción 1 en cambio, cada vez que abrís el cuaderno desde la URL estás obteniendo la versión más reciente directamente.
