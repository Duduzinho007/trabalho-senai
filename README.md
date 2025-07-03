#include <stdio.h>

int main() {
float salbruto,salliquido,soma;
int cont=0,quant;    
printf("informe a quantidade de funcionários\n");
scanf("%d",&quant);

while(cont < quant){
printf("\ninforme o seu salário bruto:\n");
scanf("%f",&salbruto);

    
    if(salbruto > 5000){
      salliquido = (salbruto-salbruto*0.28);  
        printf("seu salário liquido é:\n %.2f",salliquido);
        printf("\ndesconto de 28%");
    }
else{
salliquido = (salbruto-salbruto*0.13);
    printf("\nseu salário liquido é: %.2f",salliquido);
        printf("\ndesconto de 13%");
  }
  cont=cont + 1;
    }
    
    
 
    return 0;
}



    