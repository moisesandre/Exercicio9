# Exercicio9

#include <stdio.h>
#include <stdlib.h>

int main()

{
    system("color 0b");
    printf("Tabela de Polegadas para Centimetros\n");

    for (int pol=1; pol<=20; pol++)
    {
        printf("%d pol = %.2f cm\n", pol, pol*2.54);
    }
return 0;

}
