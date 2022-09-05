# ps
//Area of foundation
#include<stdio.h>
#include<math.h>
void main()
{
float P,SBC,a,A; 
printf("Enter the value of P\n");
scanf("%f",&P); 
printf("Enter the value of SBC of soil\n");
scanf("%f",&SBC);
a=P/SBC;
printf("Area of cross section: %f \n",a); 
A= (sqrt(a)); 
printf("Area of foundation: %f×%f \n",A,A);
}
