✅ Task 1: Calculate Factorial Using a Function
📝 Problem Statement
Write a Python program that:

Defines a function named factorial that takes a number as an argument and calculates its factorial using a loop or recursion.

Returns the calculated factorial.

Calls the function with a sample number and prints the output.

📤 Expected Output
For example, if the function is called with 5, it should return:

The factorial of 5 is: 120

Code:- 
 def factorial (n):

    if n<2:
        return 1
    else:
        return n * (factorial(n-1))
    try:
    n = int(input("Enter a integer: "))
    if n < 0:
        print("Factorial is not defined for negative numbers.")
    else:
        result = factorial(n)
        print(f"The factorial of {n} is: {result}")
        
    except ValueError:
    print("Please enter a valid integer.")


✅ Task 2: Using the Math Module for Calculations
📝 Problem Statement
Write a Python program that:

Asks the user for a number as input.

Uses the math module to calculate:

Square root of the number

Natural logarithm (log base e)

Sine of the number (in radians)

Displays the calculated results.

📤 Expected Output
For example, if the user enters 25, the output should look like:

Square root of 25: 5.0  
Natural logarithm of 25: 3.2188758248682006  
Sine of 25 (radians): -0.13235175009777303    

Code:- 

import math
num= int(input("Enter a Number:- "))
sqrt=math.sqrt(num)
logg=math.log(num)
sine=math.sin(num)

print("Square root of ",num,' is: ', sqrt)
print("Logarithm of ",num,' is: ', logg)
print("sin of ",num,' is: ', sine)
