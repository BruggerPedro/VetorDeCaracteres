#include <stdio.h>
#include <stdlib.h>
#define MAX 15

int main(){
  float media = 1;
  char caracteres[MAX];
  char nomes[MAX][50];
  int i = 0;
  
  //Verifica e prossegue com a contagem até 15 alunos
  while(i < MAX) {
    printf("\nOBS.:-----------------------------------------------------------\n");
    printf("Caso deseje parar de inserir valores, digite 0 para media!!! ");
    printf("\n----------------------------------------------------------------\n");


    printf("\nDigite a media do aluno (> 0 e <= 10): ");
    scanf("%f", &media);
    
    //Dá um "encerrar" na inserção de alunos
    if(media == 0) break;

    printf("\nInsira o nome do aluno: ");
    scanf("%s", nomes[i]);
    fflush(stdin);
    
    //Compara os valores da média do aluno e apresenta o resultado do mesmo
    if(media > 0 && media < 5){
      caracteres[i] = 'F';
    }
    else if(media >= 5 && media < 7){
      caracteres[i] = 'C';
    }
    else if(media >= 7 && media < 8){
      caracteres[i] = 'B';
    }
    else if(media >= 8 && media < 10){
      caracteres[i] = 'A';
    }
    else if(media == 10){
      caracteres[i] = 'S';
    }

    i++;
  }

  printf("\n--------------------------------------------------\n");
  printf("ALUNOS E SUAS CLASSIFICACOES:");
  printf("\n--------------------------------------------------\n");
  for(int j=0; j<i; j++) {
    printf("\nO aluno %s obteve a avaliacao %c!\n", nomes[j], caracteres[j]);
  }

  return 0;
}
