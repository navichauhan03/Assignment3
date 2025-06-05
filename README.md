# Assignment3

# A Program to Calculate factorial of a value
def factorial(n):
    if n<2:
        return 1
    else:
        return n * factorial(n-1)
n=int(input("Enter a number: "))
result=factorial(n)
print('Factorial of',n, 'is',result)

# This program show how to module
import math
a=int(input("Enter a number: "))

#Printing Square root of a Number
Sqrt= a ** 0.5
print('Square root of Giving Number is:', Sqrt)

#Printing Log Base of A number
print('Natural Logarithm of',a,'is: ',end='')
print(math.log(a))

#Printing Sine of a Number in Radians
print('Sine of Number in Radians is: ',math.radians(a))

