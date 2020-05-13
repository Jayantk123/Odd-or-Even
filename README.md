# Odd-or-Even
Check weather the no. is odd or even. 

#include<stdio.h>
#iinclude<conio.h>

main()
{

int num;
clrscr();

printf("enter an integer\n");
scanf("%d",&num);

if(num%2 == 0)
{
printf("Even\n");
}
else
{
printf("Odd\n");
}
getch();
}
