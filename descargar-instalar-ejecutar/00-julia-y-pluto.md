# Julia y Pluto

## ¿Qué es Julia?

Julia es un lenguaje de programación gratuito y de código abierto, diseñado especialmente para cómputo científico y matemático. Fue creado en el MIT y su primera versión pública es de 2012.

Lo que lo distingue de otros lenguajes es que combina dos cosas que suelen estar en tensión: una sintaxis sencilla y cercana a la notación matemática, y una velocidad de ejecución comparable a lenguajes de bajo nivel como C o Fortran. Dicho de otro modo: es fácil de leer y escribir, y al mismo tiempo muy rápido.

## ¿Qué es Pluto?

Pluto es un entorno de cuadernos interactivos para Julia. Un **cuaderno** es un documento que combina texto explicativo, fórmulas y código ejecutable en una sola pantalla, todo dentro del navegador.

Lo que hace especial a Pluto frente a otros entornos similares es su **reactividad**: cuando modificás una celda, todas las celdas que dependen de ella se actualizan automáticamente. Esto permite explorar conceptos de forma inmediata (por ejemplo, cambiar el tamaño de una muestra y ver al instante cómo cambia la distribución) sin necesidad de ejecutar el cuaderno entero cada vez.

Además, cada cuaderno de Pluto es un archivo `.jl` válido que gestiona sus propias dependencias, por lo que no requiere configuraciones adicionales para funcionar.

## ¿Por qué Julia y Pluto, y no Python o R?

Python y R son los lenguajes más usados en estadística y ciencia de datos, y vale la pena conocerlos. Sin embargo, cada uno tiene limitaciones que los hacen menos adecuados para este curso.

**Python** es un lenguaje de propósito general con una sintaxis limpia, pero el trabajo estadístico en Python se apoya casi siempre en bibliotecas como pandas o polars, cuya sintaxis es notoriamente engorrosa: operaciones conceptualmente simples requieren cadenas de métodos, índices especiales y convenciones que poco tienen que ver con la forma en que pensamos los problemas estadísticos. El código resultante es difícil de leer y de escribir para alguien que recién empieza.

**R**, en cambio, sí tiene una sintaxis excelente para estadística (especialmente en su ecosistema tidyverse) y es un lenguaje muy expresivo para este dominio. El problema es otro: R es un lenguaje de dominio específico, y cuando necesitás salir de ese dominio (automatizar algo, modificar un script en detalle, trabajar con estructuras de datos generales) la experiencia se vuelve incómoda. Además, sus entornos de cuadernos (R Markdown, Quarto) no son reactivos: al modificar una celda hay que volver a ejecutar el documento completo para ver el efecto, lo que interrumpe el flujo de exploración. Y en R, escribir código eficiente a veces obliga a pensar en vectorización o en evitar ciertos patrones, detalles de rendimiento que idealmente no deberían preocuparle a alguien que está aprendiendo estadística.

Julia con Pluto evita estos problemas:

- **Notación cercana a la matemática.** En Julia, escribir una fórmula estadística se parece mucho a escribirla en papel. Esto reduce la distancia entre la teoría y el código, y permite concentrarse en los conceptos en lugar de en la sintaxis del lenguaje.

- **Reactividad para aprender.** La naturaleza reactiva de Pluto es ideal para construir intuición estadística: podés modificar un parámetro (el tamaño de la muestra, la cantidad de repeticiones, los valores de la población) y observar el efecto de inmediato, sin interrumpir el hilo del razonamiento.

- **Sin configuración.** Cada cuaderno instala automáticamente los paquetes que necesita. No hace falta configurar entornos, instalar librerías por separado ni resolver conflictos de versiones.

- **Sintaxis accesible sin experiencia previa.** Julia fue diseñado para personas con formación matemática pero sin experiencia en programación. Aprender a usarlo lleva tiempo como cualquier herramienta nueva, pero la sintaxis no pone obstáculos innecesarios: lo que se escribe se parece a lo que se piensa.

- **Datos tabulares con una sintaxis consistente.** Cuando necesitás trabajar con tablas de datos, [DataFrames.jl](https://dataframes.juliadata.org/) ofrece una interfaz uniforme y predecible, sin las irregularidades que caracterizan a pandas.

  *Su principal desarrollador, Bogumił Kamiński, es economista y estadístico, profesor en la Warsaw School of Economics. Llegó a Julia por las mismas razones: la insatisfacción con pandas y la búsqueda de un lenguaje cuya notación se acercara a la forma en que los estadísticos piensan los problemas. Escribió el libro* Julia for Data Analysis *(Manning, 2023).*

---

Dicho esto, Julia tiene una comunidad más pequeña que Python o R, y encontrar ayuda en internet (especialmente en español) es más difícil. Para los problemas de este curso eso no es un obstáculo real, pero conviene saberlo.
