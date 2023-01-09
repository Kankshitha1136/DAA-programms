#include<stdio.h>
int main()
{
int number,remainder,total=0,temp;
printf("enter the number");
scanf("%d",&number");
temp=number;
while(number>0)
{
remainder=number%10;
total=total+(remainder*remainder*remainder);
number=number/10;
}
if(temp==temp)
printf("this number is armstrong number");
else
printf("this number is not armstrong number");
return 0;
}
