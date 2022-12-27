## Program 14 : Write a program to disply continue statement .
```C
#include <stdio.h>
int main()
{
  int i =0
  while ( i < 10)
  {
      if ( i == 4)
      {
          i++;
          continue;
          }
          printf("%d\n",i);
          i++;
  }
    return 0;
}
```C
** Output : 0
  1
  2
  3
  5
  6
  7
  8
  9 **
