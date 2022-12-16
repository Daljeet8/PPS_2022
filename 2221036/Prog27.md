## Program 27 : Write a program to check if a string  is palindromic .
```C
#include <stdio.h>
#include<string.h>
int main ()
{
    char word[50], temp[50];
    printf (" Enter the word to check if it is palindromic :");
    scanf ("%s",&word);
    strcpy(temp,word);
    strrev (temp);

     if(strcmp(word,temp)==0)
     {

        printf(" The word entered is pallindrome ");

     }
       else
       {
           printf(" The word entered  is not pallindromic");
       }
         return 0;
}
** Output : Enter the word to check if it is palindromic: madam
            The  word entered is palindromic 
            
             Enter the word to check if it is palindromic : happy 
             The word is not palindromic .**
