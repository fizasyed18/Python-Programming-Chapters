# Loops

Loops are used to execute a block of code repeatedly until a condition is met or all items in a sequence are processed. The main types are:

- For loops (iterating over sequences)
- While loops (executing code based on a condition).

## **1. For Loops**

A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).

**Looping Through a String**\
Even strings are iterable objects, they contain a sequence of characters.

**The break Statement**\
With the break statement we can stop the loop before it has looped through all the items.

**The continue Statement**\
With the continue statement we can stop the current iteration of the loop, and continue with the next.

**The range() Function**\
To loop through a set of code a specified number of times, we can use the range() function. The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and ends at a specified number.

**Else in For Loop**\
The else keyword in a for loop specifies a block of code to be executed when the loop is finished.

**Nested Loops**\
A nested loop is a loop inside a loop. The "inner loop" will be executed one time for each iteration of the "outer loop".

**The pass Statement**\
for loops cannot be empty, but if you for some reason have a for loop with no content, put in the pass statement to avoid getting an error.

## **While Loop**

While loop repeatedly executes a block of code as long as the given condition remains true. When the condition becomes false, the line immediately after the loop in the program is executed.

**The break Statement**\
With the break statement we can stop the loop even if the while condition is true.

**The continue Statement**\
With the continue statement we can stop the current iteration, and continue with the next.

**The else Statement**\
With the else statement we can run a block of code once when the condition no longer is true.

**Nested Loops**\
A nested loop is a loop inside another loop. The inner loop executes completely for every iteration of the outer loop.
