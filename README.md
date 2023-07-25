#include <stdio.h>
int main()
{
    int avg, sum =0;
    int i;
    int marks[5];

    marks[0]=60;
    marks[1]=78;
    marks[2]=97;
    marks[3]=81;
    marks[4]=55;

    for(i=0;i<=4;i++)
        sum = sum +marks[i];

    avg =sum/5;
    printf("\nAverage marks = %d",avg);
    return 0;
}
