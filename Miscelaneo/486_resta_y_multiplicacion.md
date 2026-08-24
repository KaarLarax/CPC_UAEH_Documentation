https://omegaup.com/arena/problem/resta_y_multiplicacion/#problems

# 486. Resta y multiplicación
#### Autor: Jorge Fernández Quezada (jofeque)

## Descripción
Haz un sencillo programa que lea 4 variables nombradas $A$, $B$, $C$ y $D$. Y calcula e imprima la multiplicación de la diferencia de $A$ y $B$ con la diferencia de $C$ y $D$. $(A - B * C - D)$

## Entrada
Cuatro números enteros.

## Salida
El producto de la diferencia con 4 variables de acuerdo al ejemplo.

## Ejemplo

### Entrada
```
10 6 8 3
```
### Salida
```
20
```

## Notas


## Temas identificados
### Matemáticas
- Resta de números enteros.
- Multiplicación.
- Jerarquía de operaciones.
- Operaciones aritméticas básicas.

### Programación
- Entrada y salida de datos.
- Variables enteras.
- Operadores aritméticos.
- Uso de paréntesis para agrupar operaciones.

## Propuesta de solución
#### Autor: 

Se deben leer los cuatro valores de entrada y obtener las dos diferencias: $A-B$ y $C-D$. Después, se multiplican ambos resultados para obtener el valor final.

La operación puede representarse mediante la expresión:

$$
resultado = (A-B)(C-D)
$$

## Implementación
### C++

#### Autor: 
```cpp
#include <bits/stdc++.h>

using namespace std;

int main()
{
    cin.tie(0); ios_base::sync_with_stdio(false);
    int a, b, c, d;
    cin >> a >> b >> c >> d;

    cout << (a - b) * (c - d);

}
```
