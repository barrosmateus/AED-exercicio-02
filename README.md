# AED-exercicio-02

#include <stdio.h>

main(){

    float lado, perimetro, area;
    
    printf("qual o comprimento do lado do quadrado em m²?");
    scanf("%f", &lado);
    
    perimetro = 4 * lado;
    area = lado * lado;
    
    printf("o perimetro do quadrado de lado %fm² é %fm² e sua area mede %fm².", lado ,perimetro, area);
    
}
