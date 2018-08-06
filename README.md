# -2018-01-PI-SHLG-_T05
Un programa que te indica si un caracter es minúscula, mayúscula, un número o un caracter no válido (ninguno sde los anteriores).)

#include <stdio.h>

int main()
{
    char x;
    printf("Escribe un caracter: ");
    scanf("%c", &x);

        if (x>47 && x<58) {
        printf("\n%c es un numero.", x);
        }else if (x>64 && x<91) {
        printf("\n%c es una letra mayuscula.", x);
        }else if (x>96 && x<123) {
        printf("\n%c es una letra minuscula.", x);
        } else {
        printf("\n%c es un caracter no valido");
        }

    return 0;
}
