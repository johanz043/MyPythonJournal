# Control Flow
Control flow determines how the program decides what to do. It is how the code makes decisions and repeats actions.

There are two main parts of control flow: Conditional logic (decisions) and Loops (repetition).

## Conditional Logic

#### if Statements
Allows the program to run a certain code depending if a condition is true.
E.g.
  x = 10
  if x > 9:
    print("This number is double digits")

#### elif and else
elif -> "else if"
else -> everything else not covered by if statements
  E.g. score = 75
       if score >= 90:
         print("A")
       elif score >=70:
         print("B")
       else
         print("C or below")

#### Comparison Operators
- "==" equal
- "!=" not equal
- ">" greater than
- "<" less than
- ">=" greater/equal
- "<=" less/equal

#### Logical Operators
- "and" True if both conditions are true
- "or" True if at least one condition is true
- "not" True if the condition isn't true
Python treats certain values as True or False automatically. For example, values such as 0, 0.0, empty string, empty array, none, etc are treated as false.

## Loops
Loops allow you to repeat code multiple times, it is expecially useful for iterating through arrays

#### For Loops
Used to iterate through over a sequence.
E.g. for i in array
It can be used along with range()
E.g. for i in range(3) #0, 1, 2, 3

#### While Loops 
Repeats a code while a condition is true.
E.g. count = 0

while count < 5:
    print(count)
    count += 1

#### Break, Continue and Pass
- break exits a loop immediately
- continue skips the current iteration
- pass does nothing
