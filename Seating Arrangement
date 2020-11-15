#include <stdio.h>
 
int main()
{
    int T,i,N[100000];
    scanf("%d",&T);
    for(i=0;i<T;i++)
    {
        scanf("\n%d",&N[i]);
    }
    for(i=0;i<T;i++)
    {
        if(N[i]%6==0||N[i]%6==1)
        {
            if(N[i]%12==0)
                printf("%d WS",N[i]-11);
            else if(N[i]%12==1)
                printf("%d WS",N[i]+11);
            else if(N[i]%6==0)
                printf("%d WS",N[i]+1);
            else
                printf("%d WS",N[i]-1);
            printf("\n");
        }
        else if((N[i]-2)%3==0)
        {
            if(N[i]%12==2)
                printf("%d MS",N[i]+9);
            else if((N[i]-3)%12==2)
                printf("%d MS",N[i]+3);
            else if((N[i]-6)%12==2)
                printf("%d MS",N[i]-3);
            else
                printf("%d MS",N[i]-9);
            printf("\n");
        }
        else
        {
            if((N[i]-3)%12==0)
                printf("%d AS",N[i]+7);
            else if(N[i]%12==4)
                printf("%d AS",N[i]+5);
            else if(N[i]%12==9)
                printf("%d AS",N[i]-5);
            else
                printf("%d AS",N[i]-7);
            printf("\n");
        }
    }
}
