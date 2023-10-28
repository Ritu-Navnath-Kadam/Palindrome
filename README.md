# Palindrome
#include<stdio.h>
void main()
{

int n,l=0,r,m,p;
printf("Enter any number :");
scanf("%d",&n);
p=n;
   while(n>0)
 {
  m=n%10;
  l=l*10+m;
  n/=10;
 }
 
 if(l==p)
 printf("It is palindrome");
 else
 printf("It is not palindrome");
 
}
    
