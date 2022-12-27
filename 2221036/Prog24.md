 ## Program 24 : Write a code to display to check if given number is prime .
 ```C
 #include <stdio.h>
int main ()
{
     int num , i, count =0;
     printf ( " Enter the number here : ");
     scanf (" %d",&num);
     for ( i=2;i<num-1;i++)
     {
         if( num%i==0)
         {
             count=1;
             break;
         }
     }
     if (num==1)
     {
         printf (" 1 is neither prime not composite");
     }
    if (count==0)
    {
    printf (" Number is prime ");
    }
    else
    printf(" Number is not prime");
    return 0 ;
}
** Output : Enter your number to check - 72
            72 is not prime number . 
            
            Enter a number to check 43
            43 is prime number .
            
            Enter a number to check - 110
            110  is not prime number.


