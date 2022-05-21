#include <stdio.h>

int main() {

    int n;

    char ch[100];

    printf("enter number:");

    scanf("%d",&n);

    sprintf(ch,"%d", n);

    printf("%s",ch);

    return 0;

}

