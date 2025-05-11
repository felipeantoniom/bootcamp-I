# bootcamp-I
criando repositorio para a disciplina

#include <stdio.h>

int main() {
    float num1, num2, num3, media;
    
    // Solicita os números ao usuário
    printf("Digite três números para calcular a média:\n");
    printf("Primeiro número: ");
    scanf("%f", &num1);
    printf("Segundo número: ");
    scanf("%f", &num2);
    printf("Terceiro número: ");
    scanf("%f", &num3);
    
    // Calcula a média
    media = (num1 + num2 + num3) / 3;
    
    // Exibe o resultado
    printf("\nA média dos números %.2f, %.2f e %.2f é: %.2f\n", 
           num1, num2, num3, media);
    
    return 0;
}
