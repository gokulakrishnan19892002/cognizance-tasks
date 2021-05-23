#include <stdio.h>
#include <stdlib.h>
#include <math.h>
int main()
{
    int steps;
    int x;
    printf("Enter x the coordinate of friend's house(1<=x<=1000000):");
    scanf("%d",&x);
    {
    if(x<1 || x>1000000)
    {
        printf("Enter the coordinate value which is x>=1 and x<=1000000");
        exit(0);
    }
    }
    if(x>=5 && x%5==0)
    {
        steps=x/5;
        printf("The minimum number of steps that the elephant needs to take to reach friend's house %d",steps);
    }
    else
    {
        steps=x/5;
        steps=steps+1;
        printf("The minimum number of steps that the elephant needs to take to reach friend's house %d",steps);
    }
   
}

