https://omegaup.com/arena/problem/Clasico-A--B-/#problems

# 9383. Clasico A + B
#### Autor: Emmayueru - Kun (emmayuerukun)

## Descripción
Bastante Facil, Solo es la Suma de 2 Numeros.

## Entrada
La entrada consiste en 2 números separados con un espacio: A, B 1<=A<=B<100.

## Salida
La salida consiste en un entero representando el resultado de la Suma

## Ejemplo

### Entrada
```
2 2
```
### Salida
```
4
```
### Entrada
```
5 6
```
### Salida
```
11
```
### Entrada
```
5 5 
```
### Salida
```
10
```

## Notas


## Temas identificados
### Matemáticas
- Suma de números enteros.
- Operaciones aritméticas básicas.

### Programación
- Entrada y salida de datos.
- Variables enteras.
- Operador de suma.
- Operaciones aritméticas.

## Propuesta de solución
#### Autor: mae
La solución consiste en obtener los valores de $A$ y $B$ mediante la entrada estándar y aplicar la operación de suma. Debido a que el problema únicamente requiere calcular el resultado de sumar ambos números, no es necesario utilizar estructuras de control o algoritmos adicionales.

## Implementación
Declarar dos variables enteras para almacenar los valores ingresados. Después, se utiliza el operador + para calcular la suma y se imprime el resultado mediante cout.

### C++

#### Autor: 
```cpp
#include <bits/stdc++.h>

using namespace std;

int main()
{

    cin.tie(0); ios::sync_with_stdio(false);

    int a, b;
    cin >> a >> b;

    cout << a + b;
}
```
