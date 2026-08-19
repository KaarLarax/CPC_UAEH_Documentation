https://omegaup.com/arena/problem/Acumulando-Monedas/#problems

# Título 4588. Acumulando Monedas
#### Autor: Coding Rush

## Descripción
A los voluntarios el Coding Rush les gusta mucho jugar MonsterBall Go, y están planeando hacer una excursión al terminar esta sesión. Mario quiere revisar cuántos gimnasios hay en el camino, pues cada gimnasio le da  $10$  MonsterMonedas.

Como está muy ocupado siendo un voluntario del Coding Rush, no tiene tiempo para hacer cuentas, así que te pidió ayuda para decirle cuántas MonsterMonedas tendrá al terminar la excursión, si sabe que va a pasar por  $N$  gimnasios.


## Entrada
Un entero, $N$, que representa la cantidad de gimnasios en el camino.

## Salida
Un número, $K$, que representa la cantidad de MonsterMonedas que Mario tendrá al terminar la excursión.

## Ejemplo

### Entrada
```
5
```
### Salida
```
50
```
### Entrada
```
3
```
### Salida
```
30
```

## Notas


## Temas identificados

### Programación
- Entrada y salida.

## Propuesta de solución
#### Autor: Ema
Para resolver el problema, primero se lee el número entero $N$, que representa la cantidad de gimnasios.
Como cada gimnasio proporciona 10 MonsterMonedas, por lo que la solución es $N$ multiplicado por $10$.

## Implementación
Leer e imprimir $N$ seguido de un $0$.

### C++

#### Autor: Ema
```cpp
#include <bits/stdc++.h>

using namespace std;
int main()
{
    cin.tie(0); ios_base::sync_with_stdio(false);

    int n;
    cin >> n;
    
    cout << n << 0;

}
```
