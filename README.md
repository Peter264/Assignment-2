# Assignment-2
// Online C compiler to run C program online
#include <stdio.h>

int main() {
   int age;
   float income;
   
   // user to input age
  printf("Enter your age:");
  scanf("%d",&age);
  
  // user to input annual income
 printf("enter your annual income :");
 scanf("%f",&income);
 
 if (age>=21&&income>=21000) { printf("congratulations you qualify for the loan \n");}
 else { printf ("unfortunately we are unable to offer you a loan now \n");}

    return 0;
}
