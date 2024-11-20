#include <stdio.h>

int main() {
    
    
// Definindo variáveis para os atributos da cidade
    
    in

 
int codigo; // Código da cidade
    
    ch

   
char nome[50]; // Nome da cidade
    
   
long int populacao; // População da cidade
    
    fl
float area; // Área da cidade em km²
    
 
double pib; // PIB da cidade em milhões
    
    i

  
int pontos_turisticos; // Número de pontos turísticos

    // Cadastro das Cartas
    
    pr

  
printf("=== Cadastro de Cartas - Cidades ===\n");

    

    pri


   
printf("Digite o código da cidade: ");
    scanf("%d", &codigo);

    printf("Digite o nome da cidade: ");
    
   
scanf(" %[^\n]s", nome); // Lê uma string incluindo espaços

    

    prin


    p


 
printf("Digite a população da cidade: ");
    
   
scanf("%ld", &populacao);

    

    print


    p


 
printf("Digite a área da cidade (em km²): ");
    
    sca
scanf("%f", &area);

    

    p
printf("Digite o PIB da cidade (em milhões): ");
    scanf("%lf", &pib);

    

    pr
printf("Digite o número de pontos turísticos: ");
    
  
scanf("%d", &pontos_turisticos);

    // Exibição dos Dados das Cartas
    
    p
printf("\n=== Dados da Carta Cadastrada ===\n");
    printf("Código: %d\n", codigo);
    printf("Nome: %s\n", nome);
    
    prin

    pr

   
printf("População: %ld\n", populacao);
    printf("Área: %.2f km²\n", area);
    
   
printf("PIB: %.2lf milhões\n", pib);
    printf("Pontos Turísticos: %d\n", pontos_turisticos);

    

  
return 0;
}
Detalhes Importantes

