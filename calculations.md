# Basic Calculations
Python follows PEMDAS:
- Parentheses ()
- Exponents **
- Multiplication/Division
- Addition/Subtraction

## Addition (+)
Addition works with both integers and floats.
  E.g. print(5 + 2) = 7
       print(2.5 + 1.2) = 3.7
However, when used with strings or arrays, it cause concatenation.
  E.g. print("5" + "3") = "53"
  E.g. nums = {1, 2, 1} 
       nums + nums = {1, 2, 1, 1, 2, 1}

## Subtraction (-)
Subtraction works with both integers and floats
  E.g. print(3.5 - 1.5) = 2

## Multiplication (*)
Multiplies values
  E.g. print(3 * 5) = 15
Also work with strings
  E.g. print("Hi " * 3) = Hi Hi Hi

## Division (/)
The division operation always returns a float, not an integer
  E.g. print(10/2) = 5.0

## Floor Division (//)
Floor division returns an integer, rounding the output to the nearest whole number, it also works with negative numbers.
  E.g. print(7//2) = 3

## Modulus/Remainder (%)
Returns the remainder of a division operation
  E.g. print(7 % 2) = 1
       print(3 % 3) = 1

## Exponentiation/Powers (**)
Raises a number to a power
  E.g. print(2 ** 3) = 8
       print(5 ** 2) = 25

## = Vs ==
"=" assigns a value to a variable
  E.g. x = 5
"==" compares two values and asks if they're equal
  E.g. x = 5
       print(x==5) = True
       print(x==3) = False

