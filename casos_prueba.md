# Casos de prueba

Las pruebas están integradas en el notebook
`src/Taller_3_Discretas.ipynb`, inmediatamente después de cada ejercicio.

Cada bloque utiliza instrucciones `assert` para verificar los resultados.

## Casos obligatorios

- César: `HOLA UNAL`, con `k = 3`, produce `KROD XQDO`.
- RSA: `p = 61`, `q = 53`, `e = 17`, `M = 65`, produce `C = 2790`.
- MPC: `[40, 35, 50, 25]` produce suma `150` y promedio `37.5`.
- Dijkstra: `Portal` a `Centro` tiene distancia `20`.
- Simplificación: `Σm(1,3,5,7)` se simplifica como `C`.
- Qubit: se verifican `X|0> = |1>`, `H|0>` y `HH|0> = |0>`.
