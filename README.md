# super-triunfo
#include <stdio.h>

// Desafio Super Trunfo - estados
// Tema 1 - Cadastro das cartas
// Objetivo: No nível novato você deve criar as cartas representando as cidades utilizando scanf para entrada de dados e printf para exibir as informações.

int main() {
  // Área para definição das variáveis para armazenar as propriedades das cidades
    char nome[50];
    long populacao;
    float area;
    float pib;
    int expectativa_vida;
    char codigo_iso[4];
  
  // Área para entrada de dados
  
 printf("=== CADASTRO DE CARTA - SUPER TRUNFO ESTADOS ===\n");

    printf("Nome do país: ");
    scanf(" %[^\n]", nome);

    printf("População: ");
    scanf("%ld", &populacao);

    printf("Área (km²): ");
    scanf("%f", &area);

    printf("PIB (US$): ");
    scanf("%f", &pib);

    printf("Expectativa de vida: ");
    scanf("%d", &expectativa_vida);

    printf("Código ISO (3 letras): ");
    scanf("%s", codigo_iso);

  // Área para exibição dos dados da cidade
  printf("\n=== CARTA CADASTRADA ===\n");
    printf("Nome: %s\n", nome);
    printf("População: %ld\n", populacao);
    printf("Área: %.2f km²\n", area);
    printf("PIB: %.2f US$\n", pib);
    printf("Expectativa de vida: %d anos\n", expectativa_vida);
    printf("Código ISO: %s\n", codigo_iso);
return 0;
} 
