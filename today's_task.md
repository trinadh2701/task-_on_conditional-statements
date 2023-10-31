Write a Python program that asks the user for their age and prints "You are an adult" if the age is 18 or older, otherwise prints "You are a minor'


```python
Age = int(input('enter a age'))

if Age>=18:  # if age is above 18 or age is equla to 18
    print('you are adult')
elif Age<=18:  # if age is below 18
    print(' you are minor')
else:
  print('enter correct age')
```

    enter a age45
    you are adult
    

Write a program that takes a numerical grade (out of 100) as input and prints the corresponding letter grade according to the following scale:
 90-100: A
 80-89: B
 70-79: C
 60-69: D
 Below 60: F



```python
x = int(input('enter a marks'))

if x>=90:  # if x are above 90  or equal to 90
  print('A')
elif x>=80:  # if x are above 80 or equal to 80
  print('B')
elif x>=70:  # if x are above 70 or equal to 70
  print('C')
elif x>=60:  # if x are above 60 or equal to 60
  print('D')
elif x<60:  # if x are below 60
  print('F')
else:
  print('invalid')
```

    enter a marks95
    A
    

Write a program that calculates the Body Mass Index (BMI) of a person. The user should input their weight in kilograms and height in meters. The program should then print whether the person is underweight, normal weight, overweight, or obese



```python
w=float(input('your weight in kilograms'))
h=float(input('your hight in centimeter'))
bmi=w/(h**2) #formula of boday mass index

if bmi<18.5 # if bmi is below 18.5
  print('under weight')
elif bmi>=18.5 and bmi<24.9: # if bmi is below 18.5 and bmi is equal to 24.9
  print('nrml weight')
elif bmi==25 and bmi<=29.9: # if bmi is equla to 25 and bmi is equal or greater than 29.9
  print('over weight')
else:
  print('obesity')
```

    your weight in kilograms400
    your hight in centimeter3
    obesity
    


```python
Write a program that asks the user for three numbers and prints the maximum of the three.
```


```python
x=int(input('enter a value '))
y=int(input('enter a value '))
z=int(input('enter a value '))

if x>y and x>z: # x is grater than y and x greater than z
  print('highest number',(x))
elif y>x and y>z: # y is greater than x and y greater than z
  print('highest number',(y))
elif z>x and z>y: # z is graeater than x and z is greater than y
  print('highest number',(z))
else:
  print('invalid')
```

    enter a value 75
    enter a value 83
    enter a value 23
    highest number 83
    

Write a program that asks the user for a temperature (in Celsius) and prints "It's freezing" if the temperature is below 0, "It's cool" if it's between 0 and 10, "It's warm" if it's between 10 and 20, and "It's hot" if it's above 20



```python
x=float(input('tempeature in celsius'))

if x<0: # x is below in  0
  print('its freezing')
elif 0>x<10: # x is above in 0 and x is below in 10
  print('its cool')
elif 10<x<20: # x is above in 10 and x is below in 20
  print('its warm')
elif x>20: # x is above in 20
  print('its hot')
else :
  print('invalid')
```

    tempeature in celsius45
    its hot
    

Write a program that asks the user for a number (1-7) and prints the corresponding day of the week.



```python
x=int(input('enter a number'))

if x==1: # if the given number is equal to 1 then it will executes print statement
    print('sunday')
elif x==2:
    print('monday')
elif x==3:
    print('tuesday')
elif x==4:
    print('wednesday')
elif x==5:
    print('thusday')
elif x==6:
    print('friday')
elif x==7: # if and elif statements will not correct then it executes else statement
    print('saturday')
else:
    print('enter valid number')
```

    enter a number5
    thusday
    

Write a program that asks the user for a number and prints "In range" if the number is between 10 and 20 (inclusive), and "Out of range" otherwise


```python
x=int(input('enter a number'))

if x in range(9,21): # x is in the range between 9 and 21 
    print('the given number is In range(inclusive)')
else:
    print('the given number is out of range')
```

    enter a number12
    the given number is In range(inclusive)
    

Write a program that asks the user for an integer and prints whether it's even or odd


```python
x=int(input('enter a number'))

if x%2==0: # if x is divisible by 2 and equal to 0
    print('even number')
else:
    print('odd number')
```

    enter a number64
    even number
    


 Write a Python program to add 'ing' at the end of a given string (string length should be equal to or more than 3). If the given string already ends with 'ing' then add 'ly' instead.If the string length of the given string is less than 3, leave it unchanged



```python

```


```python
x=input('enter a string  ')

if len(x)==2:  #3-->it checks len of elements in the given input ,whether len is equal to 2 or not if yes it will executes its print statement.
    print((x))
elif x.endswith('ing'): ##--> when x is endswith --> that mean if x is ended with ing it executes print statement
    print((x).replace('ing','ly')) ##-->if input was ended with 'ing',it replaces 'ly' in the place of 'ing'
else:
    print((x)+('ing'))
```

    enter a string  string
    strly
    


```python

```
