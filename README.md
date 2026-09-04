1- 

#include <stdio.h>

int main() {
    char nome[50];
    int idade;

    printf("Digite seu nome: ");
    scanf("%49s", nome);

    printf("Digite sua idade: ");
    scanf("%d", &idade);

    printf("Ola %s, voce tem %d anos.\n", nome, idade);

    return 0;
}

2- 

#include <stdio.h>

int main() {
    float raio;
    float area;
    const float PI = 3.14159;

    printf("Digite o raio do circulo: ");
    scanf("%f", &raio);

    area = PI * raio * raio;

    printf("Area do circulo: %.2f\n", area);

    return 0;
}

3-

#include <stdio.h>

int main() {
    float nota1, nota2, nota3;
    float media;

    printf("Digite a primeira nota: ");
    scanf("%f", &nota1);

    printf("Digite a segunda nota: ");
    scanf("%f", &nota2);

    printf("Digite a terceira nota: ");
    scanf("%f", &nota3);

    media = (nota1 + nota2 + nota3) / 3;

    printf("Media: %.1f\n", media);

    return 0;
}
