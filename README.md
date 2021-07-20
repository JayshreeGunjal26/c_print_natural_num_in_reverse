# c_print_natural_num_in_reverse

/* c program to print all natural numbers from n to 1 in reversed order. 
* Question- 1. Write a c program to print all natural numbers in reversed order from  1 to n , using while loop .
* Owner    - Jayshree Balasaheb Gunjal.
* batch    - PPA9.
*/
// solution :

#include<stdio.h>
#include<conio.h>

void main()
{
 int i , n;

 printf("Please enter a value of n :\n ");
 scanf("%d",&n);

 printf("first %d reversed order natural numbers are :\n",n);

 i = n ;
 while( i >= 1)
 {
 printf("%d\n",i);
 i--;
 }
 printf("********** END **********\n");
 getch();
}
