#include <stdio.h>
int main() {
    int x,y,z;
    printf("Digite o 1° número: ");
    scanf("%d",&x);
    printf("\nDigite o máximo de repetições: ");
    scanf("%d",&y);
    printf("\n");
    for(z=0;z<=y;z++){
        printf("%d x %d = %d\n",x,z,x*z);
    }
    return 0;
}
