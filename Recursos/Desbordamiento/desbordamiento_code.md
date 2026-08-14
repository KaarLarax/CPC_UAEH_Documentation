# Animación de desbordamiento
#### Autor: Jordan

Animación en la consola para demostrar el desbordamiento de una variable entera.

# Implementación
## C++

### Entrada
Recibe un número entero $a$, que corresponde a la cantidad de números que mostrará desde antes de desbordarse y después de desbordarse.

```cpp
#include <bits/stdc++.h>

using namespace std;

int main()
{
    int a;
    cout << "-------------- DESBORDAMIENTO --------------\n";
    cin >> a;
    int numero = INT_MAX - a + 1;

    cout << "\n";

    while (numero != INT_MIN) {
        cout << '\t' << numero << "\n\n";

        numero++;

        for (int i = 0; i < INT_MAX; i++){}
    }

    if (numero == INT_MIN) {
        cout << "-----------------------------  <--_"
             << "\n                                   |"
             << "\n            Aqui se excede el valor maximo"
             << "\n              y vuelve a su valor minimo\n\n";
        for (int j = 0; j < INT_MAX/2; j++){}
    }

    while (numero != INT_MIN + a) {
        cout << '\t' << numero << "\n\n";

        numero++;

        for (int i = 0; i < INT_MAX; i++){}
    }



    return 0;
}
```
