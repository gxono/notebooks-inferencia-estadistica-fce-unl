# Descargar e instalar Pluto

Pluto es un paquete de Julia, por lo que se instala desde el gestor de paquetes integrado. Hay dos formas de hacerlo.

## Opción 1: modo interactivo (con `]`)

### 1. Abrir la consola de Julia

Abrí una terminal y ejecutá:
```
julia
```
Deberías ver el texto `julia>` en la pantalla.

### 2. Entrar al gestor de paquetes

Presioná la tecla `]`. El texto cambiará a:
```
(@v1.x) pkg>
```

> **¿Dónde está la tecla `]`?** En teclados en español suele estar a la derecha de la letra P, o bien se accede con `Alt Gr + ]` dependiendo del modelo. Si no la encontrás, usá la Opción 2.

### 3. Instalar Pluto

Escribí:
```
add Pluto
```
y presioná Enter. Julia descargará e instalará Pluto y sus dependencias. Esto puede tardar unos minutos la primera vez.

### 4. Volver a la consola

Presioná `Backspace` o `Ctrl+C` para salir del gestor de paquetes y volver al texto `julia>`.

---

## Opción 2: usando `Pkg` directamente

### 1. Abrir la consola de Julia

Abrí una terminal y ejecutá:
```
julia
```

### 2. Instalar Pluto con Pkg

Cuando veas el texto `julia>`, escribí exactamente lo siguiente y presioná Enter:
```julia
import Pkg; Pkg.add("Pluto")
```

Julia descargará e instalará Pluto automáticamente. Útil si tuviste problemas encontrando la tecla `]`.
