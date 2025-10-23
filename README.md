# code2grow-day-2
the smart bill splitter by c program
#include<stdio.h>
int main()
{
float mealcost,tax,tip,totalbill,friend1,friend2,friend3;
printf("enter meal cost,tax,tip");
scanf("%f%f%f,&mealcost,&tax,&tip");
tax=mealcost*0.05;
tip=mealcost*0.10;
totalbill=tax+mealcost+tip;
friend1=totalbill/2;
friend2=totalbill/2;
friend3=0;
printf("total bill;%.2f\n");
printf("each friend should pay as follows\n");
printf("friend1,%.2f\n");
printf("friend2,%.2f\n");
printf("friend3,%.2f\n");
printf("totalbill,friend1,friend2,friend3");
return 0;
}
