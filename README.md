# Program-5E
C module 5
EX NO-5)e)a C program to calculate the Product of given natural numbers using Recursion
DATE:20/10/25
NAME:JADE ADRINA J
REF NO:25017000
AIM:TO Write a C program to calculate the Product of given natural numbers using Recursion'
ALGORITHM:
1)Take a number as input from the user.2)define a recursive function with return num*sum(num-1).3)call the function and display the result.
PROGRAM:
```
#include<stdio.h>
int sum(int num)
{
    if(num==1)
    return 1 ;
    else
    return num*sum(num-1);
}
int main()
{
    int n;
    scanf("%d",&n);
    printf("Product is = %d",sum(n));
}
```
OUTPUT:
<img width="850" height="288" alt="Screenshot 2025-10-20 085701" src="https://github.com/user-attachments/assets/32f4feb1-f21e-44a1-bd54-44c4f1f3eda7" />
RESULT:
Thus, a C program to calculate the Product of given natural numbers using Recursion has been executed successfully.

