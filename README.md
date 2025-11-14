# ASSIGNMENT-3-Functions-Modules-in-Python
Module 4: Functions &amp; Modules in Python 
TASK 1
def factorial(n):
    if n == 0 or n == 1:
        return 1
    return n * factorial(n - 1)
num = int(input("Enter a number to calculate its factorial: "))
result = factorial(num)
print("Factorial of", num, "is:", result)

TASK 2
import math
num = float(input("Enter a number: "))
square_root = math.sqrt(num)
natural_log = math.log(num)
sine_value = math.sin(num)
print("Square root of", num, "is:", square_root)
print("Logarithm (ln) of", num, "is:", natural_log)
print("Sine of", num, "in radians is:", sine_value)
