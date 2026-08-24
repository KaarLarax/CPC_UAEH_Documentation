https://omegaup.com/arena/problem/Brayan-y-su-bendicion/#problems

# 5651. Brayan y su bendicion

#### Autor: Alexis Lozano Teran (lolzano)

## Descripción
En un universo muy paralelo Brayan es padre de 7 bendiciones.

Se acerca el cumpleaños de uno de sus hijos, pero como Brayan en un pasado de luchador recibio varios golpes, sillas, escaleras y un monton de cosas en su cabeza; no se acuerda de cuantos años cumplira su hijo este año (2017). Por suerte, el todavia se acuerda el lugar donde estan los certificados de nacimiento de cada uno, donde indica la fecha en la que su hijo nacio.

Como Brayan es muy malo para las matematicas te pidio ayuda a vos para que teniendo la informacion del año en que nacio, le digas cuantos años esta cumpliendo este año (2017), pero como tu tambien eres malo en matematicas, pero sabes programar diseñas un programa que te diga la respuesta.


## Entrada
Un numero entero $n$ que indica el año en el que nacio el hijo de Brayan.

## Salida
Un numero entero $a$ que indica los años que cumple el hijo de Brayan el 2017

## Ejemplo

### Entrada
```
2010
```
### Salida
```
7
```
### Entrada
```
2007
```
### Salida
```
10
```
### Entrada
```
1998
```
### Salida
```
19
```

## Notas
- $1900 \leq n < 2017$
- $1 \leq a \leq 117$
- Este problema no esta en contra de ningun profesor de matematicas del colegio de Brayan, ni del tuyo.
- Este problema toma el año actual como el 2017. (por si vienes del futuro)


## Temas identificados
### Matemáticas
- Resta de números enteros.
- Cálculo de edades.
- Diferencia entre años.

### Programación
- Entrada y salida de datos.
- Variables enteras.
- Operaciones aritméticas.
- Resta de números enteros.

## Propuesta de solución
#### Autor: mae
Para obtener la edad que cumple el hijo de Brayan durante el año 2017, se debe restar el año de nacimiento $n$ al año actual establecido en el problema, que es 2017.

## Implementación
Leer $N$ e imprimir esta operación:  $2017$ - $n$ 

### C++

#### Autor: mae
```cpp
#include <bits/stdc++.h>

using namespace std;

int main()
{
    cin.tie(0); ios::sync_with_stdio(false);

    int n;
    cin >> n;

    cout << 2017 - n;
}
```
