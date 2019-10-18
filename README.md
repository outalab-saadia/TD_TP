# TD_TP 1
Exercice1
programmation
#include <stdio.h>
#include <math.h>
int main()
{
// declaration de variable
float a,b,c,d,x1,x2;
// lecture des donner
printf("donner la valeur de a,b,c\n");
scanf("%f","%f","%f",&a,&b,&c);
if((a==0)&&(b!=0))
{
x1=-(c/b);
printf("la solution est;%f",x1);
}
else
d=b*b-(4*a*c);
if(d==0)
{
x1=-(b/2*a);
x2=-(b/2*a);
}
else
if(d>0)
{
 x1=(-b+sqrt(d))/2*a;
 x2=(-b-sqrt(d)/2*a;
 }
 else
 printf("x1=%f",-b,"+i",sqrt(-i));
 printf("x1=%f",x1);
 }
