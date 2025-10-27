# GIT-python
Task-1 and Task-2

 Task-1
 Performs the basic mathematical operations on these two numbers:
o	Addition
o	Subtraction
o	Multiplication
o	Division

Task-2
 Problem Statement: Write a Python program that:
1.  Takes a user's first name and last name as input.
2.  Concatenates the first name and last name into a full name.
3.  Prints a personalized greeting message using the full name.


code:
Task-1
"""Task 1: Perform Basic Mathematical Operations
Problem Statement: Write a Python program that does the following:
1.  Takes two numbers as input from the user.
2.  Performs the basic mathematical operations on these two numbers:
o	Addition
o	Subtraction
o	Multiplication
o	Division"""

#lets assume the iput numbers are 'a' and 'b' and the result is 's'

#for addition

a=float(input('enter the 1st value:'))
b=float(input('enter the 2nd value:'))
s=a+b
print('the result is:',s)

#for d+Substraction
a=float(input('enter the 1st value:'))
b=float(input('enter the 2nd value:'))
s=a-b
print('the result is:',s)

#for multiplication
a=float(input('enter the 1st value:'))
b=float(input('enter the 2nd value:'))
s=a*b
print('the result is:',s)

#for division
a=float(input('enter the 1st value:'))
b=float(input('enter the 2nd value:'))
s=a/b
print('the result is:',s)

Task-2
"""Task 2: Create a Personalized Greeting
Problem Statement: Write a Python program that:
1.  Takes a user's first name and last name as input.
2.  Concatenates the first name and last name into a full name.
3.  Prints a personalized greeting message using the full name.
"""

first_name = str(input('Enter your first name: '))
last_name = str(input('Enter your last name: '))
full_name = first_name + ' ' + last_name
print('hello,', full_name,'welcome to the python program.')
