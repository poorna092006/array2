#include <stdio.h>
 int main (){
    printf("poorna jain 590012779\n");
    int n;
    printf("Enter the number of rows of the triangle = ");
    scanf("%d", &n);

    for ( int i = 1; i<=n; i++ )
    {
        for ( int j = 1; j<=i; j++ )
        {
            printf("* " );

        }
        printf("\n");
    }
    return 0;
 }
