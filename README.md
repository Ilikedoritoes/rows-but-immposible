#include <stdio.h>

void main()

{

    int n,i,j;

    printf("Enter size of triangle\n");

    scanf("%d",&n);
    
    if (n > 0)
    {
        for(i=0;i<n;i+=2)

        {

            for(j=0;j<=(n-i)/2;j++)  

                printf(" ");

            for(j=0;j<=i; j++)

                printf("*");

            printf("\n");

        }
    }
    else
    {
        printf("Ilegal input size");
    }
    
}
