# Descida-da-ladeira













#include <stdio.h>
#include <stdlib.h>
#include <locale.h>




int main()
{
    float matriz [3][5];
    int menu;
    setlocale(LC_ALL, "Portuguese");
    menup:
    menu=0;
    system("cls");
    printf("**********MENU PRINCIPAL**********\nDIGITE A OPÇÃO DESEJADA APERTE ENTER\n\n");
    printf("1. Bateria 1 \n");
    printf("2. Bateria 2 \n");
    printf("3. Bateria 3 \n");
    printf("4. Obter classificação geral na tela \n");
    printf("5. Exportar classificação geral \n");
    printf("6. Sair do sistema \n");
    scanf("%d",&menu);


        if(menu==1)
            {
            menu1:
            system("cls");
            printf("**********Bateria 1**********\nDIGITE O TEMPO DA BATERIA 1 DE CADA UMA DAS EQUIPES:\n\n");
            printf("1.Tempo da equipe 1 na bateria 1:\n");
            printf("2.Tempo da equipe 2 na bateria 1:\n");
            printf("3.Tempo da equipe 3 na bateria 1:\n");
            printf("4.Tempo da equipe 4 na bateria 1:\n");
            printf("5.Tempo da equipe 5 na bateria 1:\n");
            printf("6. Voltar ao menu principal  \n");
            scanf("%d",&menu);
            if(menu==6){goto menup;}

            }

            if(menu==2)
                {
                menu2:
                system("cls");
                printf("**********Bateria 2**********\nDIGITE O TEMPO DA BATERIA 2 DE CADA UMA DAS EQUIPES:\n\n");
                printf("1.Tempo da equipe 1 na bateria 2:\n");
                printf("2.Tempo da equipe 2 na bateria 2:\n");
                printf("3.Tempo da equipe 3 na bateria 2:\n");
                printf("4.Tempo da equipe 4 na bateria 2:\n");
                printf("5.Tempo da equipe 5 na bateria 2:\n");
                printf("6. Voltar ao menu principal  \n");
                scanf("%d",&menu);
                if(menu==6){goto menup;}
                }

                if(menu==3)
                    {
                    menu3:
                    system("cls");
                    printf("**********Bateria 3**********\nDIGITE O TEMPO DA BATERIA 3 DE CADA UMA DAS EQUIPES:\n\n");
                    printf("1.Tempo da equipe 1 na bateria 3:\n");
                    printf("2.Tempo da equipe 2 na bateria 3:\n");
                    printf("3.Tempo da equipe 3 na bateria 3:\n");
                    printf("4.Tempo da equipe 4 na bateria 3:\n");
                    printf("5.Tempo da equipe 5 na bateria 3:\n");
                    printf("6. Voltar ao menu principal  \n");
                    scanf("%d",&menu);
                    if(menu==6){goto menup;}
                    }
                    if(menu==4)
                        {
                        menu4:
                        system("cls");
                        printf("**********CLASSIFICAÇÃO GERAL DAS EQUIPES:**********\n\n");
                        printf("1° lugar – EQUIPE X – Tempo (minutos:segundos:mili-segundos):\n");
                        printf("2° lugar – EQUIPE X – Tempo (minutos:segundos:mili-segundos):\n");
                        printf("3° lugar – EQUIPE X – Tempo (minutos:segundos:mili-segundos):\n");
                        printf("4° lugar – EQUIPE X – Tempo (minutos:segundos:mili-segundos):\n");
                        printf("5° lugar – EQUIPE X – Tempo (minutos:segundos:mili-segundos):\n\n\n\n");
                        printf("Digite 1 para voltar ao menu principal   \n");
                        scanf("%d",&menu);
                        if(menu==1){goto menup;}
                    }




    return 0;
}
