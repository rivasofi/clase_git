Sistemas Electrónicos Embebidos   -   Programación en C
## **Selección Simple**
1. Realizar un programa que sea capaz de indicar si un número dado es mayor, menor, o igual a cero.
``` c
#include <stdio.h> // para manejar pantalla y teclado
int main(){
    
    int numero;
    printf("Pone un numero: ");
    scanf ("%d",&numero); //toma la nota y el prociento d es que es decimal
    if    (numero>0){
        printf("Mayor a cero");
    }
    
    if (numero==0){
        printf("Es igual a cero");
    }
    if (numero<0){
        printf("El numero es menor a cero");
    }
    return 0;
}
```