##Program 31 : Write a program to display to use of function .
```C
#include <stdio.h>
int add( int a , int b );
   int main ()
   {
       int m = 20 , n= 30 , sum ;
       sum = add (m,n);
       printf(" sum is %d", sum );
       return 0;
   }

      int add ( int a ,int b )
      {
          return ( a+ b);
      }
```C
**Output : 50 **
