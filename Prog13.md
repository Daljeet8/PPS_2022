## Program : Write a program to show the use of break statement.
```C
#include <stdio.h>
int main()
{
  int i =0;
  while (i<10)
  {
      if(i==7)
  {
   break;
   }
   printf("%d\n",i);
   i++;
  }
  return 0;
}
** Output : 0 
  1
  2
  3
  4
  5
  6 **
