# DAY-2

Markdown Headings:



Ordered and Unordered list:


Bold and Italic:

**Python Programming**
 *python Programming*

Linking URL:
[click here](https://tinyurl.com/introduction-to-python)


Inserting an image:
![image](https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885__340.jpg)
<img src="https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885__340.jpg" width=200 height=200 >

C:
#include<stdio.h>
Void main()
{
printf(“Hello World!!”);
}

Save → .c
Compile 
Run

Introduction to Python:

1. Different paradigms
2. Interpreted PL
3. open source
4. Object Oriented PL

Numeric Data types:
1. int
2. float
3. Complex

Example:

a = 10 #integer
b = 23.34 #float
c = 12+3j #Complex number
print(type(a),type(b),type(c))

Example:
c1 = 4+5j
c2 = complex(6,8)
print(c1+c2)
print(c2.real)#real part of the complex number
print(c2.imag)#imaginary part of the complex number


input and output functions:
#input --> input()
#output --> print()
a = int(input("Enter the value of a"))
b = int(input("Enter the value of b"))
#end-->new line
#sep -->space
print(a+b,end=" ")
print(a-b,a*b,a/b,sep=",")

Operators:symbol which performs some specific task
Operands : values given to operator are known as operands

Arithmetic operators:
 +,-,*,/,%,//(floor division),**(exponent)
Example:

a = int(input("enter a value"))
b = int(input("enter b value"))
print(a + b)
print(a - b)
print(a * b)
print(a / b)#float quotient
print(a % b)#Remainder
print(a // b)#int quotient
print(a ** b)# 2 5

Relational operators:
 <,>,<=,>=,==,!=
print(a < b)#True
print(a > b)
print(a <= b)
print(a >= b)
print(a == b)
print(a != b)

Logical operators:
and,or,not -->return type - Boolean
#print(help("keywords"))
print(a < b and a>1)
print(a < b or a>1)
print(not a < b)

Membership operators :
 in,not in

list1 = [12,23,34,45,56,67]
print(12 in list1)#True
print(120 in list1)#False
print(12 not in list1)#False
print(120 not in list1)#True


Conditional statements:if,else,elif
if a < b:
    print("a is less than b")
elif a > b:
    print("a is greater than b")
else:
    print("a or equals to b")

Question : Find the largest of three numbers 
a = int(input("enter a value"))
b = int(input("enter b value"))
c = int(input("enter c value"))
if a>b and a>c:
    print("largest number is a:",a)
elif b>c:
    print("largest number is b:",b)
else:
    print("largest number is c:",c)

Loops : while,for
# print 1 to n values
n = int(input("enter n value"))
i = 1
while i<=n:
    print(i,end=" ")
    i += 1#i=i+1
Output:
enter n value10
1 2 3 4 5 6 7 8 9 10

    

