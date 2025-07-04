# Task 1
n=int(input('Enter a number: '))
def factorial(n):
    if 0<=n<2:
        return 1
    else:
        return n*(factorial(n-1))
result=factorial(n)
print('Factorial of ',n,' is: ',result)


# Task 2
n=int(input('Enter a number: '))
from math import *
print( 'Square root: ',sqrt(n))
print('Logarithm: ',log(n))
print('Sine: ',sin(n))
