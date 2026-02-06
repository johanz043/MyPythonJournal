# Variables and Data Types

## Variables

#### Variable 
A name that stores values. A variable must start with a letter or underscore and cannot use keywords such as if, for, while, etc.
E.g. x=10, name="Johanz", student=True
You can use type() to check data types (e.g. print(type(x)) will output the type of variable.

#### Integers
Refers to whole numbers either positive or negative.
E.g. a=5, b=-3

#### Floating Numbers (floats)
Numbers with decimal points.
E.g. a=5.34, b=-2.3
Note: Floating numbers are not always perfect for calculations due to the way computers store decimals.

#### Strings (str)
Text data, between quotation marks.
E.g. message = "Hello"

#### Boolean 
True or false values
E.g. light_on = True, light_on = False


## Type Casting (Type Conversion)
Type casting allows you to convert one data type into another.
Functions such as int(), float() and str() can convert the inputed text into their respective type as long as the inputs match the type.
E.g.
   int("10") = 10
   int(3.9) = 3
   float(5) = 5.0
   str(True) = "True"
You can also use it in a print statement:
  print("i am " + str(age) + " years old")

## Output using print()
The print() function displays the parameters on the screen.
  E.g. print("Hello World")
It can also print different values.
  E.g. print("Age: ", 20)

## Input using input()
The input() function gets an input from a user. However, it will always return a string.
  E.g. name = input("Enter your name: ")
       print(name)
If you want it to return a value other than a string you will need to type cast it.
  E.g. int(input("Enter your age: "))
In this case, it converts the string into an integer.




