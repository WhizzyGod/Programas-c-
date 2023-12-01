// Programas c Ivan Andres Caicedo castro 
//1. Un estudiante desea saber cuál será su calificación final en la materia de programación. Dicha calificación se compone de los siguientes porcentajes:
#include <stdio.h>

int main() {
    float nota1, nota2, nota3, examen_final, trabajo_final, calificacion_final;

    printf("Introduce la primera nota parcial: ");
    scanf("%f", &nota1);

    printf("Introduce la segunda nota parcial: ");
    scanf("%f", &nota2);

    printf("Introduce la tercera nota parcial: ");
    scanf("%f", &nota3);

    printf("Introduce la calificación del examen final: ");
    scanf("%f", &examen_final);

    printf("Introduce la calificación del trabajo final: ");
    scanf("%f", &trabajo_final);

    calificacion_final = (nota1 + nota2 + nota3) / 3 * 0.55 + examen_final * 0.30 + trabajo_final * 0.15;

    printf("La calificación final es: %.2f\n", calificacion_final);

    return 0;
}



// segundo programa 2. Una tienda ofrece un descuento del 15% sobre el total de la compra y un cliente desea saber cuanto deberá pagar finalmente por su compra.
#include <stdio.h>

int main() {
    float total_compra, total_pagar;

    printf("Introduce el total de la compra: ");
    scanf("%f", &total_compra);

    total_pagar = total_compra * (1 - 0.15);

    printf("El total a pagar después del descuento es: %.2f\n", total_pagar);

    return 0;
}
