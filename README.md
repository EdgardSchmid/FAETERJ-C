# Aula-1-C-faculdade
Primeira aula de C da faculdade | Scan e cálculos 


# include <stdio.h>
int main () {
	/*int idade;
	printf ("Qual é a sua idade? Vou te dizer o dobro dela. ");
	scanf ("%d", & idade);
	int dobro = idade * 2;
	printf ("O dobro da sua idade  é %d.", dobro);

	// escreva um progrtem C que leia o nome e o peso de uma pessoa. Ao final, infome algo como:
	// Maria pesa 58.3kg!

	char nome[10];
	float peso;
	printf ("Qual é o seu nome? ");
	scanf ("%s", nome);
	printf ("Qual é o seu peso? ");
	scanf ("%f", & peso);
	printf ("Seu nome é %s e seu peso é %.2f! ", nome, peso);

// Crie um programa que pergunte a un aluno seu nome, nota 1 nota 2 e informe a média. 
// João Victor, sua média foi 6!

char nome[50];
float nota1;
float nota2;
float media;

printf ("Qual é o nome do aluno? ");
scanf ("%s", nome);
printf("Qual foi a nota do aluno no primeiro semestre? ");
scanf ("%f", &nota1);
printf ("Qual foi a nota do aluno no segundo semestre? ");
scanf ("%f", &nota2);

media = ((nota1 + nota2) / 2);

printf ("A nota do(a) %s foi %.2f! ", nome, media);

// Faça um programa em x que leia dois valores, base e altura. Após isso calcule a are área de um triângulo
// (Base * Altura / 2)

float base;
float altura;
float area;

printf ("Digite uma base: ");
scanf ("%f", & base);
printf ("Digite uma altura: ");
scanf ("%f", & altura);
area = (base * altura) / 2;
printf ("A área do seu triângulo é %.2f! ", area);

// Ano atual * ano de nascimento para saber idade.

int nascimento;
int atual;
int idade;

printf ("Fale o ano atual: ");
scanf ("%d", & atual);
printf ("Agora fale o ano do seu nascimento: ");
scanf ("%d", & nascimento);

idade = atual - nascimento;

printf ("Você tem %d anos! ", idade);

// Antecessor e sucessor:

int num;
int antes;
int depois;

printf ("Escolha um número: ");
scanf ("%d", & num);

antes = num - 1;
depois = num + 1;

printf ("O sucessor do número %d é %d e o antecessor é %d! ", num, depois, antes);

// Soma de números

int num1;
int num2;
int total;
int multiplicação;

printf ("Escolha um número: ");
scanf ("%d", & num1);
printf ("Escolha outro: ");
scanf ("%d", & num2);

total = num1 + num2;

printf ("%d é o resultado da soma.\n", total);

multiplicação = num1 * num2;

printf ("%d é o resultado da multiplicação.", multiplicação); 

// mercado

char nome[50];
int quantidade;
float valor;
float total;

printf ("Escolha um produto: ");
scanf ("%s", nome);
printf ("Quanto esse produto custa? ");
scanf ("%f", & valor);
printf ("Quantos desse produto você quer comprar? ");
scanf ("%d", & quantidade);

total = quantidade * valor;

printf ("O total da sua compra do produto %s deu R$%.2f! ", nome, total); */

// Perímetro:

int base;
int altura;
int perímetro;

printf ("Fale a base do retângulo: ");
scanf ("%d", & base);
printf ("Fale a altura agora: ");
scanf ("%d", & altura);

perímetro = 2 * (base + altura);

printf ("O perímetro é %d.", perímetro);

	return 0;
}
