# Lambda Functions

Lambda functions are small anonymous functions, meaning they do not have a defined name. These are small, short-lived functions used to pass simple logic to another function.

- Contain only one expression.
- Result of that expression is returned automatically (no return keyword needed).

**Syntax**

`lambda arguments : expression`

## Key Objectives

**Lambda with Built-in Functions**

Lambda functions are commonly used with built-in functions like map(), filter(), and sorted().

**1. Using Lambda with map()**

   `map()` function in Python applies a function to every element of one or more iterables and returns a map object (iterator) containing the transformed      results. It is commonly used for element-wise operations and can often replace explicit loops with shorter and more readable code.

  -	**String Manipulation with map()**
    
    a. Converting strings to uppercase
   	b. Extracting first character from strings
    c. Removing whitespaces from strings

**2. Using Lambda with filter()**

   `filter()` function is used to extract elements from an iterable (like a list, tuple or set) that satisfy a given condition. It works by applying a function to each element and keeping only those for which function returns True.

**4. Using Lambda with sorted()**

   The `sorted()` function can use a lambda as a key for custom sorting

**5. Multiply all numbers with reduce()**

`reduce()` applies the lambda step by step, multiplying values from left to right.

**Use Cases**

**1. Condition Checking**

   Lambda function can use conditional expressions (if-else) to return different results based on a condition.

**2. List Comprehension**

   Lambda can be combined with list comprehensions to apply the same operation to multiple values in a compact way.

**3. Returning Multiple Results**

   Although a lambda can contain only one expression, it can still return multiple results by combining them into a tuple.

