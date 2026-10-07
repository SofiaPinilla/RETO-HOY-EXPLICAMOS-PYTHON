# Hoy enseñáis vosotros — Repaso de Python

## Equipos 

| Grupo | Integrantes | Tema para el reto 2 |
| --- | --- | --- |
| 1 | CHRISTIAN_VAZQUEZ (MDIA) · ANDRES_GIMENO (MDIA) · RAUL_FERRIS (MDES) | Variables, tipos y strings |
| 2 | OSCAR_HERREROS (MDIA) · Laura Soler Úbeda (MDIA) · ANTONIO_NAVARRO (MDES) | Listas y tuplas |
| 3 | PABLO_CUNAT (MDIA) · LORENZO_SABBATINI (MDIA) · NICO_GOMEZ (MDES) | Diccionarios y sets |
| 4 | Jana Mei Cervera Monzó (MDIA) · IGNACIO-PINAZO (MDIA) · JAIME_SANFELIX (MDES) | Operadores y condicionales |
| 5 | FRAN_ALAPONT (MDIA) · RAFA_BROTONS (MDIA) · DAVID_GALLART (MDES) | Bucles for |
| 6 | ADRIAN_LAZARO (MDIA) · JUANJO_PRADES (MDIA) · MARIO_GONZALEZ (MDES) | while, break y continue |
| 7 | JORGE_DURA (MDIA) · PABLO_LEGORBURO (MDIA) · IGNACIO_IBÁÑEZ-RIZO (MDES) | Funciones, parámetros y docstrings |
| 8 | ANGEL_CARLOS_PEREZ (MDIA) · ALEJANDRO-CERVERA (MDIA) · RICARDO_ROMAN (MDES) | Funciones lambda |
| 9 | JORGE_OLIVER (MDIA) · HUGO_GAVILAN (MDIA) · CARLOS_GUTIERREZ (MDES) | input, conversiones y round |
| 10 | MANOLO_TORTAJADA (MDIA) · INGRID (MDIA) · JAVIER_MARTINEZ (MDIA) | try, except y finally |
| 11 | LOLA_BONET (MDIA) · JOAQUIN_VILLALOBOS (MDIA) | Módulos, pip y pytest |
| 12 | LUCAS_OSEJO (MDIA) · JADE_LOPEZ (MDIA) | Debugging |

## Objetivo

Cada equipo preparará un ejemplo del tema asignado en la tabla y saldrá a explicarlo. Entre todos repasaremos las tres clases de Python.

## Qué prepara cada grupo

- Un ejemplo pequeño y claro, que podáis explicar al resto de la clase.
- La salida o el resultado esperado y una ejecución comprobada.
- Una modificación o un error típico que ayude a entender el concepto.
- Una pregunta para que el resto prediga qué va a pasar. Escuchad las respuestas de la clase y después mostrad la solución.

La exposición consiste en enseñar y explicar el código directamente. No tenéis que preparar diapositivas ni una presentación adicional. Usad conceptos de las clases, sin añadir frameworks ni herramientas nuevas.

## Misiones por equipo

### Grupo 1 — Variables, tipos y strings

Pedid un nombre y una edad. Convertid la edad, mostrad los tipos y mostrad un mensaje por consola con una f-string que incluya el nombre en mayúsculas, la edad y la longitud del nombre. Explicad que input devuelve texto.

### Grupo 2 — Listas y tuplas

Cread una lista de tres productos: añadid uno, modificad otro y eliminad uno. Guardad el nombre y la ciudad de una tienda en una tupla. Explicad acceso por índice, mutabilidad y la diferencia entre ambas estructuras.

### Grupo 3 — Diccionarios y sets

Cread la ficha de un producto: consultad, añadid y modificad claves. Comparad corchetes y get con una clave que falta. Convertid una lista de categorías repetidas en un set y explicad el resultado.

### Grupo 4 — Operadores y condicionales

Clasificad tres notas usando if/elif/else: menos de 5, de 5 a menos de 9 y de 9 a 10. Mostrad una condición con and y otra con in. Probad una nota en cada tramo y explicad las comparaciones.

### Grupo 5 — Bucles for

Recorred una lista de precios, mostrad cada precio y calculad el total con un acumulador. Enseñad qué pasa en cada vuelta y por qué el acumulador se inicializa antes del bucle.

### Grupo 6 — while, break y continue

Pedid palabras hasta que se escriba salir. Usad break para terminar y continue para saltar una entrada vacía. Explicad dónde vuelve el flujo en cada caso.

### Grupo 7 — Funciones, parámetros y docstrings

Cread calcular_precio(precio, cantidad=1), con docstring y return. Llamadla con uno y dos argumentos. Explicad parámetro, argumento, valor opcional, return y la diferencia entre comentario y docstring.

### Grupo 8 — Funciones lambda

Cread una lambda que duplique un número y otra que pase un texto a mayúsculas. Llamadlas con varios valores. Comparad una de ellas con su versión escrita con def, sin usar map ni filter.

### Grupo 9 — input, conversiones y round

Pedid una cantidad con int y un precio con float. Calculad el importe con round(..., 2). Mostrad type antes y después de convertir. Explicad qué pasa al intentar convertir hola a un entero.

### Grupo 10 — try, except y finally

Pedid dos números y divididlos. Controlad entradas no numéricas y división entre cero. Mostrad un mensaje con finally. Demostrad un caso válido, uno con texto y otro con divisor cero.

### Grupo 11 — Módulos, pip y pytest

Cread operaciones.py con sumar y test_operaciones.py con al menos dos tests con assert. Importad la función, ejecutad pytest y enseñad un test que pasa y otro que falla intencionadamente. Corregid el test al terminar. Explicad para qué se usa pip.

### Grupo 12 — Debugging

Preparad vuestro propio ejemplo de código para explicar cómo funciona el debugger. Podéis utilizar un bucle y observar qué ocurre en cada iteración.

Colocad un breakpoint, ejecutad el programa paso a paso y mostrad cómo cambian los valores de las variables. Explicad al resto de la clase qué está ocurriendo y cómo os ayuda el debugger a entender la ejecución.

## Guion para salir a explicar

1. **Explicad la idea:** qué concepto os ha tocado y para qué sirve.
2. **Enseñad el ejemplo:** explicad las líneas importantes.
3. **Lanzad vuestra pregunta:** que la clase prediga el resultado o detecte el error.
4. **Ejecutad y cerrad:** mostrad el resultado y una conclusión que puedan recordar.

Todos los integrantes deben intervenir. Repartid el turno antes de salir.

## Entrega

Un repositorio por equipo con el código del ejemplo y un `README.md` breve que incluya:

- Integrantes y tema.
- Qué demuestra el ejemplo y cómo ejecutarlo.
- Resultado esperado.
- Pregunta para la clase y su respuesta.
- Error típico o modificación que habéis explicado.

Enviad el enlace a **scpinilla@edem.es** con el asunto `Explicamos Python — Grupo XX`.
