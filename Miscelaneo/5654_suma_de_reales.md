https://omegaup.com/arena/problem/Suma-de-reales/#problems

# 5654. Suma de reales 
#### Autor: Ana Sofía (sofia.aponteb)

## Descripción
Elabora un programa que sume dos números

## Entrada
Dos números reales

## Salida
La suma de los dos números con dos decimales

## Ejemplo

### Entrada
```
1
2
```
### Salida
```
3.00
```
### Entrada
```
5.5
10
```
### Salida
```
15.50
```

## Notas
Límites
-2^8 < x < 2^8


## Temas identificados
### Matemáticas
- Suma de números reales.
- Operaciones aritméticas básicas.
- Representación de números decimales.

### Programación
- Declaración y uso de variables de tipo double.
- Entrada y salida de datos.
- Operadores aritméticos
- Formateo de números decimales con fixed y setprecision(2).

## Propuesta de solución
#### Autor: mae
Crear dos variables de tipo double para almacenar los valores de entrada A y B. Posteriormente, realizar la suma de ambos valores y mostrar el resultado con dos decimales.

## Implementación
Se declaran dos variables de tipo double para recibir los números. Después, se leen los valores mediante cin, se realiza la suma utilizando el operador + y se imprime el resultado con fixed y setprecision(2) para mostrar exactamente dos decimales.

### C++

#### Autor: 
```cpp
#include <bits/stdc++.h>

using namespace std;

int main()
{
    cin.tie(0); ios_base::sync_with_stdio(false);

    double x, y;
    cin >> x >> y;
    cout << fixed << setprecision(2) << x + y;

    return 0;
}
```
