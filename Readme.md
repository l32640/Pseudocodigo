#Pseudocodigo

/*
Inicio
     Declarar variaveis
     Ecrever input
     ler input
     calculo
     escrever output
Fim
*/

#include <stdio.h>

#include <stdlib.h>

int main(void) //inicio algoritmo

{

	/*Delarar variaveis*/

	int n1, m;

	/*escreva == printf */

	printf("Escreva digito para multiplicar por ele proprio");

	/*ler == scanf */

	n1 = scanf("%d", &n1 );

	/*Calculo  m <= n1 * n1*/

	m = n1 * n1;

	/*Escreva*/

	printf("resultado e =  %d", m);

}  //fim algoritmo
 
