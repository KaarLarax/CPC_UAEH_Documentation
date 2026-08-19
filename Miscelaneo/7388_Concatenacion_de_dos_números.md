https://omegaup.com/arena/problem/Concatenacion-de-dos-numeros/#problems

# Título 7388. Concatenacion de dos números
#### Autor: 

## Descripción
Realiza un programa que lea dos números e imprima su concatenación.


## Entrada
Dos enteros $a$ y $b$, cada uno en su propia línea.

## Salida
La concatenación de ambos números.

## Ejemplo

### Entrada
```
10
8
```
### Salida
```
108
```
### Entrada
```
10
81
```
### Salida
```
1081
```

## Temas identificados

### Programación
- Entrada y salida

## Propuesta de solución
#### Autor: mae
Leer $a$ y $b$, la solución es imprimir ambos números juntos sin espacios.


## Implementación
Leer e imprimir $a$ y $b$ sin espacios.

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

    cout << a << b;

}
```


