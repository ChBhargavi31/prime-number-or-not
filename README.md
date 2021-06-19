#include<stdio.h>
int checkforprime(int);
int i;
int main()
{
int n1,primenumber;)
printf("\n recursion:check a number is prime or not:\n");
printf("input any positive number:");
scanf("%d",&n1);
i=n1/2;
primenumber=checkforprime(n1);
if(primenumber==1)
printf("the number %dis a prime number \n",n1);
else
printf("the number %d is not a prime number\n",n1);
return 0;
}
int  checkforprime(int n1)
{
if(i==1)
{
return 1;
}
else if(n1%i==0)
{
return 0;
}
else
{
i=i-1;
checkforprime(n1);
}
}
