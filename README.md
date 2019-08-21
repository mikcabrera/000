#include <stdio.h>
#include <stdlib.h>

int main()
{

char letra;
char letraMax;
char letraMin;
int numero;
int acumuladorNeg=0;
int acumuladorPos=0;
int contPos=0;
int contPares=0;
int contImpares=0;
int contCeros=0;
int maximo;
int minimo;
int flag=0;
float promedioPos;
char respuesta='s';


do {

    printf("Ingrese una letra: ");
    fflush(stdin);
    scanf("%c", &letra );

}

    printf("Ingrese un numero entre -100 y 100");
    scanf("%d", &numero);

                while (!(numero>= -100 && numero<=100)) {

     printf("Error. Ingrese numero");
     scanf("%d", &numero);

    }


        if (numero%2==0){

              contPares++;}
        else {
            cantImpares++; }

if (numero>0){

              acumuladorPos += numero;
              contPos++;}
        else {
            cantImpares++; }

    printf("Quiere seguir");
    fflush(stdin);
    scanf("%c", &respuesta);
 }

while (respuesta=="s");


if(contPos != 0)
 }
promedioPOS= (float) acumulador/contPos;


