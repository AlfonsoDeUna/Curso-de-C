

# Primeros ejercicios de punteros

Ejercicios de C básicos para mis alumnos de FP

## crea un array unidimensional que los usuarios introduzcan los valores y posteriormente puedas visualizar el contenido

### Solución

```c

#include <stdio.h>
#include <stdlib.h>

void main() {
	int numeros[10];

	for (int i = 0; i <= 9; i++) {
		int valor;
		printf("introduzca un numero por teclado:");
		scanf_s("%d", &valor);
		numeros[i] = valor;
	}

	for (int i = 0; i <= 9; i++) {
		printf("%d", numeros[i]);
	}

}
```
