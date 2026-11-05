#include<stdio.h>
#include<conio.h>
int main ()
{
 float p,r,t,si;
printf("Enter the principal:");
scanf ("%f",&p);
printf ("Enter the rate;");
scanf ("%f",&r);
printf ("Enter the time :");
scanf ("%f",&t);
si = (p * t * r)/100;
printf ("Simple interest = "%.2f",si);
return 0;
}

