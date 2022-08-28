# take-something-return-something
This is a program for functions in c programming in the way of takes something return something type.


#include<stdio.h>
#include<conio.h>
void main()
{
	int a;
	int table(int a);
	int s;
	printf("Enter one number a:");
	scanf("%d",&a);
	s=table(a);
	int table(a);
}
int factorial(int a)
{
	int i,fact=1;
	for(i=1;i<=a;i++)
	{
		fact=fact*i;
	}
	printf("Factorial of a is %d",fact);
	return(fact);
}
int table(int a)
{
	int i,table;
	for(i=1;i<=10;i++)
	{
		table=a*i;
		printf("\n %d",table);
	}
	return(table);
}
