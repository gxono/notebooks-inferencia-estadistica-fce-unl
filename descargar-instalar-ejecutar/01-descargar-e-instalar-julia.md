# Descargar e instalar Julia

## Opción 1: desde la página oficial

### 1. Descargar el instalador

Ingresá a [julialang.org](https://julialang.org/downloads/) y descargá la versión **Current stable release** correspondiente a tu sistema operativo.

### 2. Instalar

**Windows:** ejecutá el archivo `.exe` descargado y seguí el asistente. Marcá la opción **"Add Julia to PATH"** si aparece.

**macOS:** abrí el archivo `.dmg` y arrastrá Julia a la carpeta Aplicaciones.

**Linux:** descomprimí el archivo `.tar.gz` y agregá la carpeta `bin/` al PATH.

---

## Opción 2: desde la Microsoft Store (Windows)

1. Abrí la **Microsoft Store** (la podés buscar en el menú Inicio).
2. Buscá **Julia** en la barra de búsqueda.
3. Hacé clic en **Instalar**.

Esta opción configura el PATH automáticamente, por lo que es la más sencilla para usuarios de Windows.

---

## Verificar la instalación

### ¿Cómo abrir una terminal?

Una **terminal** es una ventana donde se pueden escribir comandos de texto. Para abrirla:

- **Windows:** buscá **"Terminal"** en el menú Inicio como si fuera cualquier otra aplicación.
- **macOS:** buscá "Terminal" en Spotlight (`Cmd + Espacio`).
- **Linux:** buscá "Terminal" en el menú de aplicaciones.

### Verificar que Julia quedó instalada

Con la terminal abierta, escribí el siguiente comando y presioná Enter:

```
julia --version
```

Si la instalación fue exitosa, verás un mensaje como `julia version 1.x.x`.

> **Nota:** la primera vez que Julia se ejecuta puede tardar algunos segundos en responder. Es normal — el sistema está preparando el entorno. A partir de la segunda vez es notablemente más rápido.
