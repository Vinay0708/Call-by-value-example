# Call-by-value-example
#include <stdio.h>
int swap(int x,int y)
{
    int temp;
    temp=x;
    x=y;
    y=temp;
    return (x,y);
}
void main()
{
   int a=10,b=20;
   printf("Before swapping:-%d,%d",a,b);
   swap(a,b);
   printf("After swapping:-%d,%d",a,b);
}
