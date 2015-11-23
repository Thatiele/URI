# URI - Exercicio Led
#include <stdio.h>
#include <stdlib.h>
#include <string.h>
int main()
{
    char l[1110];
    int n,soma=0,i,j;
    scanf("%d", &n);
        for(i=0 ; i < n ; i++){ // cria um vetor com o numero digitado
            scanf("%s", l);
                for( j=0 ; j < strlen(l); j++){ // o strlen calcula o numero de caracteres em uma string
        if(l[j] == '1'){ // assim, o if verifica cada numero dos leds
            soma+=2;
        }
        else if(l[j] == '2'){
            soma+=5;
        }
        else if(l[j] == '3'){
            soma+=5;
        }
        else if(l[j] == '4'){
            soma+=4;
        }
        else if(l[j] == '5'){
            soma+=5;
        }
        else if(l[j] == '6'){
            soma+=6;
        }
        else if(l[j]== '7'){
            soma+=3;
        }
        else if(l[j] == '8'){
            soma+=7;
        }
        else if(l[j] == '9'){
            soma+=6;
        }
        else if(l[j] == '0'){
            soma+=6;
        }
                }
        printf("%d leds\n",soma); // e no final apresenta os leds encontrados
            soma = 0;
        }
    return 0;
}
