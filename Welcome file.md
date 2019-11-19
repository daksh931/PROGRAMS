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

3 MATRIX PROGRAM
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
4 FACTORIAL PROGRAM
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
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTg0NjA2MzYwOSwxOTYwOTMxMDk5LDE2OD
MxMjEzNDUsLTcxNzMwMjc4MywtMjAzODYzNTMxMl19
-->