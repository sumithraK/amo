#include <stdio.h>
#include <stdlib.h>

int main()
{
    char t[30];
    int i,j,n;
    puts("Enter the Text:");
    gets(t);
    n=strlen(t);
    for(i=n;i>=0;i--)
    {
       if(t[i-1]==' '||t[i-1]==NULL )
       {
           for(j=i;t[j]!=' ';j++)
           {
               printf("%c",t[j]);
           }
       }

       printf(" ");


    }

    getche();
}
