**

# PPS PROGRAMS

## NAME DAKSH GOYAL 

## BRANCH IT A

## ROLL NO 1921020

**





 **1 : PROGRAM ON FUNCTION** 
```
`#include<stdio.h>
int name();
int daksh();
int report();


void main()
{
   report();
}

int name()
{
puts("\t\t\tDaksh");
}
```

**OUTPUT :** 
```
Guru Nanak Dev Eng. College
 Department Of Technology
          Daksh 
```
 


**2 PRIME NUMBER**
```
                                                                                                                                                 
#include<stdio.h>                                                                                                                                
int main()                                                                                                                                       
{  
int a,b,c;                                                                                                                                       
scanf("%d",&a);                                                                                                                                  

for(b=2; b<a; b++)                                                                                                                               
{                                                                                                                                                
c=a%b;                                                                                                                                           
                                                                                                                                                 
if(c==0)                                                                                                                                         
{                                                                                                                                                
printf("number is not prime %d ",a);                                                                                                                                                                                                                                                         
return 0;                                                                                                                                        
} 
}
 printf("number is  prime %d ",a);                                                                                                                
} 
```
**OUTPUT**
```
59                                                                                                                                               
number is  prime 59 
                                                                 
23                                                                                                                                               
number is  prime 23                                                                       

12 
number is not prime 12

```

**3 REVERSE OF NUMBER**
```
                                                                                                                                                 
#include <stdio.h>                                                                                                                               
int main()                                                                                                                                       
{                                                                                                                                                
    int n, reversedNumber = 0, remainder;                                                                                                        
    printf("Enter an integer: ");                                                                                                                
    scanf("%d", &n);                                                                                                                             
    while(n != 0)                                                                                                                                
    {                                                                                                                                            
        remainder = n%10;                                                                                                                        
        reversedNumber = reversedNumber*10 + remainder;                                                                                          
        n /= 10;                                                                                                                                 
    }                                                                                                                                            
    printf("Reversed Number = %d", reversedNumber);                                                                                              
    return 0;                                                                                                                                    
}                                                                                                                                                
       
```

**OUTPUT**
```
                                                                                                                                                 
Enter an integer: 569 
Reversed Number = 965  
                                               
Enter an integer: 5479963
Reversed Number = 3699745
```


**4 SUM OF ARRAY**


 ```
 


  #include <stdio.h>
   int main()
    {
     int s,a[20],i,sum=0; 
     printf("Enter the size of array but less than 20: ");
     scanf("%d",&s);
     for(i=0;i<=s;i++)
       {
       printf("Enter the value in a[%d]: ",i);    
       scanf("%d",&a[i]); 
       }
      for(i=0;i<=s;i++)
       {
         sum=sum+a[i]; 
       }
       printf("The Sum of an array is %d ",sum); return 0; }
       ```

```
**OUTPUT**
```
Enter values in array
4

Enter numbers in array
4,6,2,8

Sum of array is 20
```

**5 BUBBLE SORT PROGRAM**

```

#include<stdio.h>
void main()
{
    int array[MAXSIZE];
    int i, j, num, temp;
 
 printf("Enter the size \n");
    scanf("%d", &num);
    printf("Enter the elements one by one \n");
    for (i = 0; i < num; i++)
    {
        scanf("%d", &array[i]);
    }
    printf("Input array is \n");
    for (i = 0; i < num; i++)
    {
        printf("%d\n", array[i]);
    }
    /*   Bubble sorting begins */
    for (i = 0; i < num; i++)
    {
        for (j = 0; j < (num - i - 1); j++)
        {
            if (array[j] > array[j + 1])
            {
                temp = array[j];
                array[j] = array[j + 1];
                array[j + 1] = temp;
            }
        }
    }
    printf("Sorted array is...\n");
    for (i = 0; i < num; i++)
    {
        printf("%d\n", array[i]);
    }
}
```
**OUTPUT**
```

Enter the size                                                                                                                           
6                                                                                                                                                
Enter the elements one by one                                                                                                                    
4                                                                                                                                                
5                                                                                                                                                
2                                                                                                                                                
3                                                                                                                                                
1                                                                                                                                                
8                                                                                                                                                
Input array is                                                                                                                                   
4                                                                                                                                                
5                                                                                                                                                
2                                                                                                                                                
3                                                                                                                                                
1                                                                                                                                                
8                                                                                                                                                
Sorted array is...                                                                                                                               
1                                                                                                                                                
2                                                                                                                                                
3                                                                                                                                                
4                                                                                                                                                
5                                                                                                                                                
8                           

```





**6 CALCULATOR PROGRAM**
```
#include<stdio.h>

int face();
int face()
{




puts(" |_______________________\n|_______________________|\n|  1  |  2  |  3  |     |\n
|_____|_____|_____|_____|\n|  4  |  5  |  6  |  +  |\n|_____|_____|_____|_____|\n|  7  |  8  |  9  |  -  |\n
|_____|_____|_____|_____|\n|      0    |     |  *  |\n
|___________|_____|_____|\n


}


int main()
{
face();
}
```

**OUTPUT**

```
|_______________________|
|  1  |  2  |  3  |     |
|_____|_____|_____|_____|
|  4  |  5  |  6  |  +  |
|_____|_____|_____|_____|
|  7  |  8  |  9  |  -  |
|_____|_____|_____|_____|
|      0    |     |  *  |
|___________|_____|_____|
```

**7 FACE PROGRAM**
```
#include<stdio.h>
int face();

int face()
{
puts("_______________________\n |XXXXXXXXX |\n | ( ^ ^ ) |\n | ( 0 0 ) |\n | \ $
}




int main()
{
face();
}
```

**OUTPUT**
``` |XXXXXXXXX |
 | ( ^ ^ ) |
 | ( 0 0 ) |
 | \     / |
 |  \   /  |
 |    =    |
 ```

**8 MATRIX PROGRAM**
```
#include<stdio.h>

void main()
{
int a,b,c,d,e,f,g,h,p,q,r,s;

scanf("%d%d%d%d%d%d%d%d",&a,&b,&c,&d,&e,&f,&g,&h);
 p=a*e+b*g;
 q=a*e+b*h;
 r=c*e+d*g;
 s=c*f+d*h;

printf("|%d %d||%d %d|=|%d %d|\n",a,b,c,d,p,q);
printf("|%d %d||%d %d|=|%d %d|",e,f,g,h,r,s);
```
**OUTPUT**
```
|5 5||5 5|=|50 50|
|5 5||5 5|=|50 50|
```
**9 FACTORIAL PROGRAM**
```
#include<stdio.h>

int main()
{int c = 1;
int a,b;
scanf("%d",&a);

for(b=1; b<=a; b++)
{
c=c*b;
}
printf("Fatorial is %d\n",c);
```
**OUTPUT**
```
5
Fatorial is 120
```

**10 Perimeter Area and Volume of Square**
```
#include<stdio.h>
void square();
int main()

{square();
 return 0;
}


void square()
{
 int side;
 printf("Enter the side of square:");
 scanf("%d",&side);
 printf("\nPerimeter of square:%d",4*side);
 printf("\nArea of square:%d",side*side);
 printf("\nVolume of square:%d\n",side*side*side);
}

```
**OUTPUT**
```
Enter the side of square:3

Perimeter of square:12
Area of square:9
Volume of square:27
```

**11 NUMBER EVEN/ODD**
```

#include<stdio.h>

int main()
{

int a;
scanf("%d",&a);

if(a%2==0)
{
printf("Number is even");
}



else
{
printf("Number is odd");
}
```

**OUTPUT**
```
4
Number is even
9
Number is odd
```
**12 FACTORIAL BY RECURSION**

```
#include<stdio.h>                                                                                                                                
 int fact(int n);                                                                                                                                
                                                                                                                                                 
                                                                                                                                                 
int main()                                                                                                                                       
 {                                                                                                                                               
    int n,m;                                                                                                                                     
    printf("Enter a positive integer: ");                                                                                                        
    scanf("%d",&n);                                                                                                                              
    m=fact(n);                                                                                                                                   
    printf("Factorial is %d",m);                                                                                                                 
    return 0;                                                                                                                                    
}                                                                                                                                                
                                                                                                                                                 
                                                                                                                                                 
int fact(int n)                                                                                                                                  
 {                                                                                                                                               
    if (n>=1)                                                                                                                                    
        return n*fact(n-1);                                                                                                                      
    else                                                                                                                                         
        return 1;                                                                                                                                
 }  
```
**OUTPUT**

```
 Enter a positive integer: 
 5
 factorial is 120

 Enter a positive integer: 
 10
 factorial is 3628800
```

**13 TABLE OF USER ENTERED NUMBER**
```

#include<stdio.h>

int main()
{
int a;
scanf("%d",&a);


for(int b=1; b<=10; b++)
{
int c=a*b;

printf("%d * %d = %d\n",a,b,c);
}

}
```
**OUTPUT**
```
5
5 * 1 = 5
5 * 2 = 10
5 * 3 = 15
5 * 4 = 20
5 * 5 = 25
5 * 6 = 30
5 * 7 = 35
5 * 8 = 40
5 * 9 = 45
5 * 10 = 50
```
**14 EVEN-ODD NUMBERS IN ARRAY**
```
#include <stdio.h>


int main()
{
    int a[1000],i,n,even=0,odd=0;

    printf("Enter size of the array : ");
    scanf("%d",&n);

    printf("Enter elements in array : ");
    for(i=0; i<n; i++)
    {
        scanf("%d",&a[i]);
    }

     for(i=0; i<n; i++)
    {
          if(a[i]%2==0)
          even++;
          else
 

 - List item

         odd++;

    }
     printf("even numbers in array: %d",even);
     printf("\n odd numbers in array: %d",odd);


    return 0;
}
```
**OUTPUT**
```
Enter size of the array : 5
Enter elements in array : 9
4
5
5
5
even numbers in array: 1
 odd numbers in array: 4
 ```

**15 FAHRENHEIT CENTIGRADE PROGRAM**
```
#include<stdio.h>

int main()
{
int a;
scanf("%d",&a);
int b=a*9/5;

{a=b+32;
printf("Value in centigrade %d \n",a);
}
}
```
**OUTPUT**
```
45
Value in centigrade 113
```

**16 PUTS VALUE**
```
#include<stdio.h>
 int main()
 {
 int i,a;
 printf(Enter the number upto which numer times messgae display:");
 scanf("%d",&a);
  for(i=1;i<=a;i++)
puts(" HARD WORK IS KEY TO SUCCESS ");
return 0;
}

```
**OUTPUT**
```
Enter the number upto which numer times messgae display:6
 HARD WORK IS KEY TO SUCCESS
 HARD WORK IS KEY TO SUCCESS
 HARD WORK IS KEY TO SUCCESS
 HARD WORK IS KEY TO SUCCESS
 HARD WORK IS KEY TO SUCCESS
 HARD WORK IS KEY TO SUCCESS
```



**17 ENTER DATA/INFO**
```

#include<stdio.h>

  void data();
  int main()
  {
     data();
  }

   void data()
  {  char a[20];
     int roll,age;
     long int ph;
   printf("\nEnter your information:\n");
   printf("Name = ");
    scanf("%s",a);
  printf("\nRoll no=");
scanf("%d",&roll);
printf("\nAge = ");
 scanf("%d",&age);
 printf("\nPhone no.= ");
 scanf("%ld",&ph);

printf("\nThe name is %s\nRoll no is %d\nPhone number is %ld\nAge is %d\n",a,roll,ph,age);

}
```
**OUTPUT:**
```
Enter your information:
Name = Daksh

Roll no=1921020

Age = 25

Phone no.= 9463*****

The name is Daksh
Roll no is 1921020
Phone number is 9463****
Age is 25
```

**18 TABLE RANGE**
```
#include<stdio.h>
int main()
{
 int a,b,n;
 printf("table of:");
 scanf("%d",&a);
 printf("\n enter the starting value of range:");
 scanf("%d",&b);
 printf("\n enter the last value of range:");
 scanf("%d",&n);
 for(b;b<=n;b++)
 printf("%d x %d = %d\n",a,b,a*b);
 return 0;
 }

```
**OUTPUT**
```
table of:5

 enter the starting value of range:6

 enter the last value of range:12
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50
5 x 11 = 55
5 x 12 = 60
```

**19 Hello World Program**
```
#include<stdio.h>
int main()
{                     
 printf("\nHello world\n");
}
```
**OUTPUT**
```
 Hello world
 ```

**20 SUM OF NUMBERS**
```
    
     #include<stdio.h>
int main()
{                                                                                      
 int a;
 int b;
 int c ;
 printf("Enter two numbers to get sum:");
 scanf("%d  %d",&a,&b);
 printf(" \nThe result is :%d + %d= %d\n",a,b,c=a+b);
    return 0;
 }
```
**OUTPUT**
```
Enter two numbers to get sum:45 55
 
The result is :45 + 55= 100
```
 **21 SUM AVERAGE OF NUMBERS**
```

#include<stdio.h>
  int main()
 {                                 
     int a,b,c,d,e,sum,avg;
                                                               
   printf("Enter five numbers:");
   scanf("%d %d %d %d %d",&a,&b,&c,&d,&e);
    sum = a+b+c+d+e;
   printf("The sum is:%d\n",sum);
   avg = sum/5;
   printf("The average is:%d\n",avg);
  }
```
**OUTPUT**
```
Enter five numbers:1 2 3 4 5 
The sum is:15
The average is:3



<!--stackedit_data:
eyJoaXN0b3J5IjpbNjcxMTk1MDQ2LDE5Njc2MjYzMDUsLTEyOT
U1MTc5MzEsMTc2NDU5NTMwMCw2OTExMTU1NDgsLTc1MDEyNDM1
NSwxMTUwOTQ0MjAwLDIwNDIwODY5MjYsLTE2ODMzMDQyODUsMT
I0MzQxNDk2NywxOTkwMjA0MTUxLC0xNTk1MTg3NjA5LC0xMzk5
NDAxMzIwLDcxNzk0NzRdfQ==
-->