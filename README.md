# Python Code Practice

## Table of Contents
- [Introduction](#introduction)
- [Code Basic](#code-basic)
- [Conclusion](#conclusion)


### Introduction 
This repository is based on how I used various Python techniques and libraries to implement in my Data Analytics Project. The project starts with the basic codes of python and later get advanced by using numpy, pandas and matplotlib. 

### Code Basic 
``` Python
print(6+4*10)
print((6+4)*10)
a= 15/2.0
print(type(a))
a= eval(input("Enter first no:"))
b= eval(input("Enter second no:"))
print(a+b)
d= 450
s= eval(input("Enter the speed:"))
t= d/s
print(t)
t= 5
p= eval(input("Enter the principal:"))
r= eval(input("Enter the rate:"))
si= (p*r*t)/100
amount= p+si
print(si)
print(amount)
print("Hello"+"Python")
print('H' in 'Hello')
def voidPrint():
  print("HELLO")
voidPrint()
year= eval(input("Enter the year"))
if((year%400==0) or (year%100!=0 and year%4==0)):
  print("Leap Year")
else:
  print("Not a Leap Year")
cels= eval(input("Enter the temperature in celsius:"))
far= (cels*9/5)+32
print(far)
x,y= 20, 60
x,y = y, x+20
print(x,y)
cost_price= eval(input("Enter the cost price:"))
profit= eval(input("Enter the profit:"))
selling_price= cost_price+profit
print(selling_price)
a= 20
b= 30
print((a+b)/2)
def calculate_area(base, height, type):
  if(type=='triangle'):
    area= (1/2)*base*height
    print(area)
  elif(type=='rectangle'):
    area= base*height
    print(area)
  else:
    print("Invalid type")
calculate_area(10,20,'triangle')
calculate_area(10,20, 'rectangle')
radius= eval(input("Enter the radius:"))
area= 3.14*radius*radius
print(area)
marks1= eval(input("Enter the marks of subject-1:"))
marks2= eval(input("Enter the marks of subject-2:"))
marks3= eval(input("Enter the marks of subject-3:"))
marks4= eval(input("Enter the marks of subject-4:"))
marks5= eval(input("Enter the marks of subject-5:"))
total= marks1+marks2+marks3+marks4+marks5
avg= (total)/5
print(total, avg)
num= eval(input("Enter the number:"))
for i in range (1,6):
  print(num*i)
name= input("Enter the name:")
cl= input("Enter the class:")
age= int(input("Enter the age:"))
print(name, cl, age)
print(name + "\n" + cl + "\n" + str(age))
n1= int(input("Enter the first no:"))
n2= int(input("Enter the second no:"))
n3= int(input("Enter the third no:"))
sum1= n1+n2
sum2= n2+n3
n1= sum1
n2= sum2
print(n1, n2)
a,b,c= 10,10,10
print(a,b,c)
x= 20
x= x-5
y=x
print(y)
age= int(input("Enter the age:"))
if (age>=18):
  print("Eligible")
else:
  print("Not Eligible")
num= int(input("Enter the number:"))
if(num%2==0):
  print("Even")
else:
  print("Not Even")
marks= int(input("Enter the marks:"))
if(marks>85):
  print("Grade A")
elif(marks>70 and marks<=85):
  print("Grade B")
elif(marks>60 and marks<=70):
  print("Grade C")
elif(marks>45 and marks<=60):
  print("Grade D")
else:
  print("Grade E")
num= int(input("Enter the number:"))
if(num==0):
  print("Number is zero")
elif(num>0):
  print("Number is positive")
else:
  print("Number is negative")
for letter in 'PYTHON':
  print(letter)
arr= [10,20, 30, 40, 50]
for n in arr:
  if n%2==0:
    print(n,'is a even number')
for i in range(1,11):
  print('3 X', i, '=', 3*i)
num= int(input("Enter the number:"))
fact= 1
for i in range(num):
  fact= fact*(i+1)
print("Factorial is:", fact)
num= int(input("Enter the number:"))
i=0
while (i<=10):
  print(num,'X',i,'=', num*i)
  i=i+1
num1= int(input("Enter the first number:"))
num2= int(input("Enter the second number:"))
num3= int(input("Enter the third number:"))
if(num1>num2 and num1>num3):
  print("Largest number:", num1)
elif(num2>num1 and num2>num3):
  print("Largest number:", num2)
else:
  print("Largest number:", num3)
side1= int(input("Enter the first side:"))
side2= int(input("Enter the second side:"))
side3= int(input("Enter the third side:"))
if(side1+side2>side3 and side2+side3>side2 and side1+side3>side2):
  print("Triangle is valid")
else:
  print("Not valid")
x=0
while (x<5):
  print(x)
  x= x+1
ch= input("Enter the character:")
if(ch=='a' or ch=='A'):
  print("Vowel")
elif(ch=='e' or ch=='E'):
  print('Vowel')
elif(ch=='i' or ch=='I'):
  print('Vowel')
elif (ch=='o' or ch=='O'):
  print('Vowel')
elif( ch=='u' or ch=='U'):
  print('Vowel')
else:
  print("Consonant")
l1= list('computer')
print(l1)
l1[3]
l2= [10,2,4,5,6,20,40]
sum=0
for i in l2:
  sum= sum+i
print(sum)
```

### Conclusion
Syntax and Logic Practice with help of Python. 
