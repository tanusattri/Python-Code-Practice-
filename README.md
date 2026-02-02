# Python Code Practice

## Table of Contents
- [Introduction](#introduction)
- [Code Basic](#code-basic)
- [Conclusion](#conclusion)
- [Numpy](#numpy)
- [Pandas](#pandas)

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

### Numpy
``` Python
import numpy as np
data= np.random.randn(2,3)
print(data)
data= data*10
print(data)
data= data+data
print(data)
data.shape
data.dtype
data.ndim
data1= [10,20,0,30,40,50]
arr1= np.array(data1)
print(arr1)
data2= [[0,1,2,3,4,5],[10,20,30,40,0,50]]
arr2= np.array(data2)
print(arr2)
data3= np.empty((2,3))
print(data3)
data4= np.zeros((2,3))
print(data4)
data4.dtype
data5= np.ones((2,3), dtype= int)
print(data5)
data6= np.arange(2,7)
print(data6)
data7= np.full((2,3),8)
print(data7)
arr1= np.array([1,2,3], dtype= np.float64)
print(arr1)
arr= np.array([[1,2,3],[4,5,6]], dtype= np.float64)
print(arr)
arr_2= np.array([[1,2,3],[4,5,10]],dtype= np.float64)
arr_2>arr
arr2= arr**0.5
print(arr2)
arr= np.arange(10)
print(arr)
arr_copy= arr[5:8].copy()
arr_copy[:]= 12
print(arr_copy)
arr2d  = np.array([[1,2,3],[4,5,6],[7,8,9]])
arr2d[2] #row extracts
arr2d[0][2]
arr2d[0,2]
arr2d[0]
arr_copy = arr2d[0].copy()
arr2d[0] = 42
arr2d
arr2d[0]=arr_copy
arr2d
arr= np.array([64,64,64,64,64,64,64,64,64,64])
print(arr)
arr[1:6]
print(arr2d)
arr2d[:2]
arr2d[:2, 1:]
arr2d[1,:3]
arr2d[:3,2]
import numpy as np
names = np.array(['Bob', 'Joe', 'Will', 'Bob', 'Will', 'Joe', 'Joe'])
names =='Bob'
names[names != 'Bob']
data = np.random.randn(7,4)
data
data[names=='Bob']
data[names == 'Bob', 2:]
data[names == 'Bob', 3]
names != 'Bob'
data[~(names == 'Bob')]
arr = np.empty((8,4))

for i in range(8):
    arr[i] = i
    
arr
arr[[4,3,0,2]]
arr[[-3,-5,-7]]
arr = np.arange(32).reshape((8,4))
arr
arr[[1,5,7,2],[0,3,1,2]]
arr[[1,5,7,2]][:,[0,3,1,2]]
arr = np.arange(15).reshape((3,5))
arr
arr.T
np.dot(arr.T, arr)
arr = np.arange(16).reshape((2,2,4))
arr
arr = np.arange(10)
arr
arr = np.arange(10)
arr
np.exp(arr)
x = np.random.randn(8)
y = np.random.randn(8)
print (x)
print (y)
np.maximum(x,y)
remainder, whole_part = np.modf(arr)
print(remainder)
print(whole_part)
remainder, whole_part = np.modf(arr)
print(remainder)
print(whole_part)
xarr = np.array([1.1, 1.2, 1.3, 1.4, 1.5])
yarr = np.array([2.1, 2.2, 2.3, 2.4, 2.5])
cond = np.array([True, False, True, True, False])
result = [(x if c else y)
         for x, y, c in zip(xarr, yarr, cond)]
result
arr = np.array([0,1,2,3,45,6,7])
arr.cumsum()
values = np.array([6,0,0,2,3,5,6])
np.in1d(values, [2,3,6])
```

### Pandas
```Python
import pandas as pd
obj= pd.Series([1,2,3,4,5])
print(obj)
obj2 = pd.Series([4,7,-5,3], index=['d','b','a','c'])
obj2
obj2.index
obj2.values
obj2['a']
obj2['d'] = 6
obj2[['c','a','d']]
obj2[obj2 > 0]
obj2 * 2
import numpy as np
np.exp(obj2)
sdata = {'Ohio': 3500, 'Texas':71000, 'Oregon':16000, 'Utah':5000}
obj3 = pd.Series(sdata)
obj3
states = ['California','Ohio','Oregon','Texas']
obj4 = pd.Series(sdata, index=states)
obj4
pd.isnull(obj4)
pd.notnull(obj4)
obj3 + obj4
obj4.name = 'population'
obj4.index.name = 'state'
obj4
```

### Conclusion
Syntax and Logic Practice with help of Python using libraries like NumPy, Pandas.  
