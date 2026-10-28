# Registro de errores de programación

## Registro de errores

| Fecha | Mi error | Corrección | Explicación |
|---|---|---|---|
| 2026-10-23 | | | |
| 2026-10-24 | Tuve dificultades para predecir el resultado de un bucle `while` que utilizaba el índice de una lista. | Seguir el valor del índice y comprobar la condición del bucle en cada iteración. | Un bucle `while` continúa mientras su condición sea verdadera. Los índices de las listas comienzan en `0` y el índice debe actualizarse cuando sea necesario para evitar un bucle infinito. |
| 2026-10-24 | Tuve dificultades para recorrer un diccionario y acceder a sus valores. | Utilizar `for clave in diccionario:` para recorrer las claves y `diccionario[clave]` para acceder a cada valor. | Recorrer directamente un diccionario permite obtener sus claves, no sus valores. |
| 2026-10-24 | Tuve dificultades para seguir una función que combinaba un diccionario, condiciones, un acumulador y un contador. | Seguir las variables paso a paso y comprobar las condiciones antes de actualizar el acumulador o el contador. | Cada variable cambia únicamente cuando se ejecuta la instrucción de asignación correspondiente. |
| 2026-10-26 | Inicialicé el acumulador dentro del bucle `for` e intenté sumar los números sin conservar correctamente el total acumulado. | Inicializar el acumulador antes del bucle y actualizarlo en cada iteración con `total = total + numero`. | Si el acumulador se reinicia dentro del bucle, pierde el valor anterior. Para sumar una secuencia, debe conservar el total entre iteraciones. |
| Fecha | Mi error | Corrección | Explicación |
|---|---|---|---|
| 2026-10-27 | Al predecir la salida de un programa, dije que `print(income)` imprimiría `35` en lugar de `100`. | Seguir el valor de cada variable por separado y comprobar cuál se utiliza en cada `print()`. | `income` conserva el valor `100`; calcular `savings` no modifica esa variable. |


## Reglas que debo recordar

- `total = total + numero` acumula valores.
- `contador = contador + 1` cuenta ocurrencias.
- `% 2 == 0` comprueba si un número es par.
- `return` devuelve un valor a quien llama a la función; no lo imprime.
- `print()` muestra un valor en pantalla.
- Un bucle `for` recorre los elementos de una secuencia o las claves de un diccionario.
- `diccionario[clave]` permite acceder al valor asociado a una clave.
- Un bucle `while` continúa mientras su condición sea verdadera. Debo actualizar la variable de control cuando sea necesario.
- Para predecir el resultado de un programa, debo seguir los valores de las variables una iteración a la vez.
- En una suma con un bucle, debo inicializar el acumulador antes de comenzar el bucle y actualizarlo en cada iteración.
