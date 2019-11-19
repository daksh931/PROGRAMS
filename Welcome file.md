1 : PROGRAM ON FUNCTION
```#include<stdio.h>
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

OUTPUT : 
```
Guru Nanak Dev Eng. College
 Department Of Technology
          Daksh 
```
2  CALCULATOR PROGRAM
```#include<stdio.h>

int face();
int face()
{




puts(" _______________________\n|_______________________|\n|  1  |  2  |  3  | $


}


int main()
{face();}
```

OUTPUT

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

3 FACE PROGRAM
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

OUTPUT
``` |XXXXXXXXX |
 | ( ^ ^ ) |
 | ( 0 0 ) |
 | \     / |
 |  \   /  |
 |    =    |
 ```

4 MATRIX PROGRAM
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
OUTPUT
```|5 5||5 5|=|50 50|
|5 5||5 5|=|50 50|
```
5 FACTORIAL PROGRAM
```#include<stdio.h>

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
OUTPUT
```
5
Fatorial is 120
```

6 Perimeter Area and Volume of Square
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
OUTPUT
```
Enter the side of square:3

Perimeter of square:12
Area of square:9
Volume of square:27
```

7 NUMBER EVEN/ODD
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

OUTPUT
```
4
Number is even
9
Number is odd
```
8 TABLE OF NUMBER
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
OUTPUT
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
9 ARRAYEVEN
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
          odd++;

    }
     printf("even numbers in array: %d",even);
     printf("\n odd numbers in array: %d",odd);


    return 0;
}
```
OUTPUT
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

10 FAHRENHEIT CENTIGRADE PROGRAM
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
OUTPUT
```
45
Value in centigrade 113
```

11 PUTS VALUE
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
OUTPUT
```
Enter the number upto which numer times messgae display:6
 HARD WORK IS KEY TO SUCCESS
 HARD WORK IS KEY TO SUCCESS
 HARD WORK IS KEY TO SUCCESS
 HARD WORK IS KEY TO SUCCESS
 HARD WORK IS KEY TO SUCCESS
 HARD WORK IS KEY TO SUCCESS
```



12  2:To fill your information
```
  // To fill your information
#include<stdio.h>

  void info();
  int main()
  {
     inf();
  }

   void info()
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
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTY0NTg5MzgxNywtMjg3NjMzNzk4LDU1NT
gyNjg5NywzMjkzOTU1NjcsMTk2MDkzMTA5OSwxNjgzMTIxMzQ1
LC03MTczMDI3ODMsLTIwMzg2MzUzMTJdfQ==
-->