#include <stdio.h>
int main() {
    int w,x,y,z;
    printf("tabuada\n\n");
    printf("Digite o número fixo para multiplicar: ");
    scanf("%d",&x);
    printf("\nDigite o máximo de repetições: ");
    scanf("%d",&y);
    printf("\nDigite o número inicial de repetições: ");
    scanf("%d",&w);
    printf("\n");
    for(z=w;z<=y;z++){
        printf("%d x %d = %d\n",x,z,x*z);
    }
    return 0;
}
