#include <stdio.h>
void main()
{
    float r,area,pi,circumference;
    printf("enter the radius of the circle:");
    scanf("%f",&r);
    pi=3.14;
    area =pi*r*r;
    circumference =2*pi*r;
    printf("area of the circle :%.2f\n",area);
    printf("circumference of circle :%.2f\n",circumference);
}
***************************************************************************
output:
enter the radius of the circle:5
area of the circle :78.50
circumference of circle :31.40
****************************************************************************
