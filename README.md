# git-github.com-poo1_t2_pedro.ranza
Repositório de Ranza, para POO 2021/2

//Laboratório 1

#include <stdio.h>
#include <string.h>
#include <stdlib.h>

struct produtos
{
    char cod_prod[15];
    char cpf[11];
    char fabri[50];
    float preco[10];
}log1;

struct cliente
{
    char cpf[11];
    char nome[100];
    char data_nasc[10];
    int cep[7];
   
}log2;

struct funcionario
{
    char cpf[11];
    char nome[100];
    char data_nasc[10];
    char data_ing[10];
}log3;

struct venda
{
    char cpf[11];
    char cod_prod[100];
    char cpf_cliente[10];
    char valor[10];
}log4;

int main(){
  int i,alter;
  
  printf("1 - Cadastrar Novo Cliente\n");
  printf("2 - Registrar venda\n");
  printf("3 - Ver relatório\n");
  printf("4 - Sair\n");
  scanf("%d", &alter);
  getchar();
  
  if (alter == 1)
        {
        int i,j;  
        for(i=0;i<200;i++){
            printf("Voce selecionou a opcao 1 - Cadastrar Novo Cliente\n");
            printf("Entre com CPF do cliente\n");
            scanf("%c", &log2(i).cpf);
            printf("Entre com nome completo do cliente\n");
            scanf("%c", &log2(i).nome);
            printf("Entre com a data de nascimento do cliente\n");
            scanf("%c", &log2(i).data_nasc);
            printf("Entre com o CEP do cliente\n");
            scanf("%d", &log2(i).cep);
            }
     return 0;
     }
     
  else if (alter == 2)
        {
        printf("Voce selecionou a opcao 2 - Registrar venda\n");
        for(i=0;i<200;i++){
            printf("Entre com CPF do funcionário\n");
            scanf("%c", &log4(i).cpf);
            printf("Entre com nome completo do cliente\n");
            scanf("%c", &log4(i).cod_prod);
            printf("Entre com a data de nascimento do cliente\n");
            scanf("%c", &log4(i).cpf_cliente);
            printf("Entre com o CEP do cliente\n");
            scanf("%d", &log4(i).valor);
            }
     return 0;
     }
     else if (alter == 3)
     
     
     
     return 0;
