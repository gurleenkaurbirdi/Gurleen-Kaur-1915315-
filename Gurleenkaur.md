
# Programming for Problem Solving
# Name:- Gurleen Kaur Birdi
# CRN:-1915315
# Branch:- CSE-C1
# submitted to :- Goldendeep Kaur Mam
***
# 1) To print name.

```#include<stdio.h>
void main()
{
puts("~~~~~~~~~~~~~~~~~~~~~~~~~~~~");
puts("My name is Guleen Kaur Birdi");
puts("~~~~~~~~~~~~~~~~~~~~~~~~~~~~");
}```
***
# 2) To print college address.

```#include<stdio.h>
int main() {

printf("\n\t\t\tGuru Nanak Dev Engineering College,");
printf("\n\t\t\tGill Road,");
printf("\n\t\t\tLudhiana , Punjab");

return 0;
}```
***
# 3) Program to add two numbers.

```#include<stdio.h>
void main() 
{                                      
int a,b,c;
printf("enter the numbers");
scanf("%d%d",&a,&b);
c=a+b;
printf("%d=%d+%d \n",c,a,b);
}```
***
# 4) Program to find quotient and remainder.

```#include <stdio.h>
int main()
 {
int a, b, quo,rem;
printf("Enter a");
scanf("%d", &a);
printf("Enter b");
scanf("%d", &b);
quo = a/ b;
rem = a % b;
printf("Quo = %d\n", quo);
printf("Rem = %d", rem);
 return 0;
}```
***
# 5) Program to swap two no.s without 3rd variable.

```#include <stdio.h>
int main() 
{                                       
 int a, b;
 printf("enter two numbers \n");
 scanf("%d%d", &a, &b);                            
 a = a + b;
 b = a - b;
 a = a - b;
 printf("a = %d\nb = %d\n",a,b);                    return 0;
}```
***
# 6) To check even or odd number.

```#include<stdio.h>
void main()
{
int a;
printf("Enter a number:");
scanf("%d",&a);
if (a%2 ==0)
{
printf("The number is even");
}
else
{
printf("The number is odd");
}
}```
***
# 7) Finding greatest of two numbers.

```#include<stdio.h>
int main() 
{
    int a,b;
    printf("Enter any two number(A and B): ");
    scanf("%d%d", &a, &b);
    
if(a>b)
printf("\nA is largest....");
else
        printf("\nB is largest.....");
    
return 0;
}```
***
# 8) To find greatest of 3 numbers.

```#include <stdio.h>
 
void main()
{
    int num1, num2, num3;
 
    printf("Enter the values of num1, num2 and num3\n");
    scanf("%d %d %d", &num1, &num2, &num3);
    printf("num1 = %d\tnum2 = %d\tnum3 = %d\n", num1, num2, num3);
    if (num1 > num2)
    {
        if (num1 > num3)
        {
            printf("num1 is the greatest among three \n");
        }
        else
        {
            printf("num3 is the greatest among three \n");
        }
    }
    else if (num2 > num3)
        printf("num2 is the greatest among three \n");
    else
        printf("num3 is the greatest among three \n");
}```
***
# 9) Program to grade to student according to percentage.

```#include<stdio.h>
void main()
{ int marks;
 printf("Enter marks:");
scanf("%d",&marks);
 if(marks<=100 && marks>90)
{ printf("Your grade is: A1\n");
}
else if(marks<=90 && marks>80)
 { printf("Your grade is A2\n");
}
else if(marks<=80 && marks>70)
{ printf("Your grade is B1\n");
}
else if(marks<=70 && marks>60)
{ printf("Your grade is B2\n"); 
 }
 else
 { printf("FAIL\n");
}
}```
***
# 10) Program to print roots of quadric equation.

```#include <stdio.h>
#include <math.h>
 
int main()
{
  int a, b, c, d;
  double root1, root2;
 
  printf("Enter a, b and c where a*x*x + b*x + c = 0\n");
  scanf("%d%d%d", &a, &b, &c);
 
  d = b*b - 4*a*c;
 
  if (d < 0) { 
    printf("First root = %.2lf + i%.2lf\n", -b/(double)(2*a), sqrt(-d)/(2*a));
    printf("Second root = %.2lf - i%.2lf\n", -b/(double)(2*a), sqrt(-d)/(2*a));
  }
  else { 
    root1 = (-b + sqrt(d))/(2*a);
    root2 = (-b - sqrt(d))/(2*a);
 
    printf("First root = %.2lf\n", root1);
    printf("Second root = %.2lf\n", root2);
  }
 
  return 0;
}```
***
# 11) Program to check year is leap or not.

```#include<stdio.h>
int main() { 

  int year,temp;

  printf("Enter teh year:");
  scanf("%d",&year);

  temp=year%4;

  if(year%100==0)
  {
     if(year%400==0)
     printf("\nLeap year...");
  }

  else
  {
    if(year%4==0)
    printf("\nLeap year...");

else
    printf("\nNot a Leap year...");
   }
  
  return 0;
}```
***
# 12) To print table of 5.

```#include<stdio.h>

int main() { int res;

for(int i=1;i<=10;i++) {

res=5*i;
    
   printf("\n5*%d=%d",i,res);
   }

   return 0;
}```
***
# 13) To make simple calculator using switch case.

```#include <stdio.h>
 
int main() {
	char Operator;
	float num1, num2, result = 0;
	
printf("\n Please Enter an Operator (+, -, *, /)  :  ");
scanf("%c", &Operator);
  	
printf("\n Please Enter the Values for two Operands: num1 and num2  :  ");
scanf("%f%f", &num1, &num2);
  	
switch(Operator)
  	{
  		case '+':
  			result = num1 + num2;
  			break;
  		case '-':
  			result = num1 - num2;
  			break;
  		case '*':
  			result = num1 * num2;
  			break;
  		case '/':
  			result = num1 / num2;
  			break;
		default:
			printf("\n You have enetered an Invalid Operator ");				    			
	}
  
printf("\n The result of %.2f %c %.2f  = %.2f", num1, Operator, num2, result);
	
return 0;
}```
***
# 14) To calculate reverse of a number.


```#include<stdio.h>
void main()
int i,n,rev=0 
i=0;
{
printf("Enter a number");
scanf("%d",&n);
while(i<=n)
{ 
rev=rev*10;
rev=rev+n%1;
n=n/10; i++
}
printf("The number is reversed");
scanf("%d",&n);
 }```
***
# 15) To check whether a no. is palindrome or not.

'''#include <stdio.h>
int main()
{
    int n, rev= 0, rem, a;
    printf("Enter an integer: ");
    scanf("%d", &n);
    a= n;
    
    while( n!=0 )
    {
        rem = n%10;
        rev = rev*10 + rem;
        n /= 10;
    }
    
    if (a == rev)
        printf("%d is a palindrome.", a);
    else
        printf("%d is not a palindrome.", a);
    
    return 0;
}'''
***
# 16) To check whether a number is prime or not.

#include <stdio.h>
int main()
{
    int n, i, flag = 0;
    printf("Enter a positive integer: ");
    scanf("%d", &n);
    for(i = 2; i <= n/2; ++i)
    {
       
        if(n%i == 0)
        {
            flag = 1;
            break;
        }
    }
    if (n == 1) 
    {
      printf("1 is neither a prime nor a composite number.");
    }
    else 
    {
        if (flag == 0)
          printf("%d is a prime number.", n);
        else
          printf("%d is not a prime number.", n);
    }
    
    return 0;
}```
***
# 17) Program to print prime no. to 100.

```#include<stdio.h>

   int main(){

int num,i,remark;

printf(" The prime numbers between 1 and 100 : \n");

   for(num=2;num<=100;++num)

  {

   remark=0;

  for(i=2;i<=numbr/2;i++){

  if((num % i) == 0){

 remark++;

  break;
     }

   }

   if(remark==0)
    printf("\n    %d ",num);

 }

  return 0;

   }```
***
# 18) Program to check whether a no. is amstrong or not.

```#include<stdio.h>
void main()
{ int a,b,rem,x=0;
 printf("Enter a number: ");
scanf("%d",&a);
 b=a;
 while(a!=0)
 {
rem=a%10;
x= x+rem*rem*rem;
 a=a/10; 
 }
 if(x==b)
printf("The number is armstrong\n");
 else  
printf("The number is not armstrong\n");
}```
***
# 19) Print different patterns.
   _ pattern 1

```#include <stdio.h>
int main() {
    
   int i,j,r;
    
   printf("Enter number of rows: ");
    scanf("%d",&r);
    
for(i=1; i<=r; ++i)
    {
        for(j=1; j<=i; ++j)
        {
            printf("%d ",j);
        }
        printf("\n");
    }
    return 0;
}```

_ pattern 2


```#include <stdio.h>
int main() {
    
   int r,i,j,num= 1;
   printf("Enter number of rows: ");
    scanf("%d",&r);
    for(i=1;i<=r;i++)
    {
        for(j=1;j<=i;++j)
        {
            printf("%d",num);
            ++num;
        }
        printf("\n");
    }
    return 0;
}```
***
# 20) Program to find largest from 1-D array.

```#include <stdio.h>
 
int main()
{
 
        int array[50], size, i, largest;
 
        printf("\n Enter the size of the array: ");
	scanf("%d", &size);
 
        printf("\n Enter %d elements of  the array: ", size);
 
        for (i = 0; i < size; i++)
		scanf("%d", &array[i]);
 
        largest = array[0];
 
        for (i = 1; i < size; i++) 
        {
		if (largest < array[i])
			largest = array[i];
	}
 
        printf("\n largest element present in the given array is : %d", largest);
 
        return 0;
 
}```
***
# 21) To find sum of N natural numbers in an array.

```#include<stdio.h>

int main() {
    printf("\n\n\t\tStudytonight - Best place to learn\n\n\n");
    int n, sum = 0, c, array[100];

printf("Enter the number of integers you want to add: ");
    scanf("%d", &n);

 printf("\n\nEnter %d integers \n\n", n);

for(c = 0; c < n; c++)
   {
        scanf("%d", &array[c]);
        sum += array[c];    // same as sum = sum + array[c]
    }

  printf("\n\nSum = %d\n\n", sum);
    return 0;
}```
***
# 22) Program to add two matrices.

```#include <stdio.h>
int main()
{
int m,n,c,d,first[10][10],second[10][10],
sum[10][10];
 printf("Enter the number of rows and columns of m$scanf("%d%d", &m, &n);
 printf("Enter the elements of first matrix\n");
   for (c = 0; c < m; c++)
      for (d = 0; d < n; d++)
         scanf("%d", &first[c][d]);

printf("Enter the elements of second matrix\n");

   for (c = 0; c < m; c++)
      for (d = 0 ; d < n; d++)
    scanf("%d", &second[c][d]);
   printf("Sum of entered matrices:-\n");

   for (c = 0; c < m; c++) {
      for (d = 0 ; d < n; d++) {
         sum[c][d] = first[c][d] + second[c][d];
         printf("%d\t", sum[c][d]);
      }
      printf("\n");
   }

   return 0;
}```
