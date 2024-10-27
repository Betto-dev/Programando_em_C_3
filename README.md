# Programando_em_C_3
Criando um Sistema.: Faça um programa que leia três valores e apresente como resultado a  soma dos quadrados dos valores lidos.

codigo funcionando 100%

// Desenvolvedor.: Adalberto Fernnandes
// Sistema Versão.: v1.0

#include<stdio.h>
#include<stdlib.h>
#include<locale.h>

int main(){
	//Blbioteca usada para que os acentos das palavras seja consideradas
	setlocale(LC_ALL, "Portuguese");
	//Declarando as variaveis
	int valor1 = 0, valor2 = 0, valor3 = 0, soma = 0, resultado1, resultado2, resultado3;
	
  //Solicitando ao usuario a entrada dos valores
	printf("Digite o primeiro valor: ");
	// Guardando os valores de entrada
	scanf("%d", &valor1);
	printf("Digite o segundo valor: ");
	scanf("%d", &valor2);
	printf("Digite o terceiro valor: ");
	scanf("%d", &valor3);
	// Processando os valores e consideando a operação aritmeticas
	resultado1 = valor1 * valor1;
	resultado2 = valor2 * valor2;
	resultado3 = valor3 * valor3;
	// Processando e mostrando os valores em execusão
	printf("O quadrado de %d é: %.2d \n",valor1 , resultado1);
	printf("O quadrado de %d é: %.2d \n",valor2 , resultado2);
	printf("O quadrado de %d é: %.2d \n",valor3 , resultado3);
	// Saida dos valores como pedi o codigo
	soma = resultado1 + resultado2 + resultado3;
	// Saida persnonalizada.
	printf("A soma dos quadrados é de: %.2d ", soma);
	
  return 0;
	
}
