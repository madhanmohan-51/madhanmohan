#include <stdio.h>
int main()
{
    int a,b,c=0,d;
    scanf("%d %d",&a,&b);
    while(a>1)
    {
        a=a-(a*(b/100));
        c+=1;
    }
    printf("%d",c);

    return 0;
}
