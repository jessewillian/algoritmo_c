# algoritmo_c
Exercicios aula algoritmos


#ex1:
Faça um algoritmo que solicita ao usuário um número real e exibe na tela a metade do
número digitado.

#include <stdio.h>
int main() {

    float numero, metadeNumero;

    printf("Dígite um número: ");
    scanf("%f", &numero);

    metadeNumero = numero / 2;
    printf("\nA metade do num é: %f\n", metadeNumero);
    }

#ex2:
Faça um algoritmo que solicite ao usuário um valor e exiba o dobro do valor.

#include <stdio.h>
int main() {

    float numero, doubleNumero;

    printf("Digite um número: ");
    scanf("%f", &numero);

    doubleNumero = numero * 2;
    printf("\nO double do numero é: %f\n", doubleNumero);
}
#ex3:
Faça um algoritmo que calcule a velocidade média de um trajeto com base na
distância percorrida e no tempo (em decimal) usado para isso.

