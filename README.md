#C-2
#include<stdio.h>
int main()
{
float length,width,area;
printf("Enyer the value of length:");
sacnf("%f",&length);
printf("Enter the value of width:");
scanf("%f",&width);
area=length * width;
printf("Area of a rectangle=%.2f square units",area);
return 0;
}
