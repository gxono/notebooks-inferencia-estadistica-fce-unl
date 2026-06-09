# Descargar e instalar Pluto

Pluto es un paquete de Julia, por lo que se instala desde el gestor de paquetes integrado. Hay dos formas de hacerlo.

## Opción 1: modo interactivo (con `]`)

### 1. Abrir el REPL de Julia

Abrí una terminal y ejecutá:
```
julia
```
Deberías ver el prompt `julia>`.

### 2. Entrar al gestor de paquetes

Presioná la tecla `]`. El prompt cambiará a:
```
(@v1.x) pkg>
```

### 3. Instalar Pluto

Escribí:
```
add Pluto
```
y presioná Enter. Julia descargará e instalará Pluto y sus dependencias. Esto puede tardar unos minutos la primera vez.

### 4. Volver al REPL

Presioná `Backspace` o `Ctrl+C` para salir del gestor de paquetes y volver al prompt `julia>`.

---

## Opción 2: usando `Pkg` directamente

### 1. Abrir el REPL de Julia

Abrí una terminal y ejecutá:
```
julia
```

### 2. Instalar Pluto con Pkg

En el prompt `julia>` ejecutá:
```julia
import Pkg; Pkg.add("Pluto")
```

Esto descargará e instalará Pluto sin necesidad de cambiar de modo. Útil si preferís no usar el gestor interactivo.
