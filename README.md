# square-of-diagonal-of-any-given-matrix-code-in-easy-way
#include&lt;stdio.h> #include&lt;conio.h> int main(){ int n,i,j,a[50][50],c,d; printf("Enter size of matrix\n"); scanf("%d",&amp;n); printf("Enter element in  matrix\n"); for(i=0;i&lt;n;i++){     for(j=0;j&lt;n;j++){         scanf("%d",&amp;a[i][j]);     } } printf("your  matrix are \n"); for(i=0;i&lt;n;i++){     for(j=0;j&lt;n;j++){        printf("%d  ",a[i][j]);     }     printf("\n"); } printf("print 1st diagonal element in matrix\n"); for(i=0;i&lt;n;i++){     for(j=0;j&lt;n;j++){             if(i==j){             c=a[i][j];                 printf("%d  ",a[i][j]*a[i][j]);             }     }  } printf("\nprint 2nd diagonal element in matrix\n"); for(i=0;i&lt;n;i++){     for(j=0;j&lt;n;j++){             if(i+j==n-1){             c=a[i][j];                 printf("%d  ",a[i][j]*a[i][j]);             }     }  }  }
