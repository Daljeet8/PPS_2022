## Program 13 : Write a program to display switch statement .
```C
#include <stdio.h>
int main()
{
  int number = 0;
   printf("enter a number :");
   scanf("%d",&number);
  switch(number)
{
    case 10:
    printf("number is equals to 10");
    break;
    case 50:
    printf("number is equal to 50");
    break;
    case 100:
    printf("number is equal to 100");
    break ;
    default:
    printf(" number is not equals to 10,50 or 100");
}
 return 0;
}
```C
** Output : enter a number :
number is not equal to 10 ,50 or 100 **
