# Functions

Python functions are reusable blocks of code used to perform a specific task. They help organize programs into smaller sections and execute the same logic whenever needed by calling the function.

**Creating a Function**\
A function is defined using the def keyword, followed by a function name and parentheses.

**Function Names**\
Function names follow the same rules as variable names in Python:\
1. A function name must start with a letter or underscore\
2. A function name can only contain letters, numbers, and underscores\
3. Function names are case-sensitive (myFunction and myfunction are different)\

Valid function names:\
- calculate_sum()\
- _private_function()\
- myFunction2()

## **Parameters vs Arguments**

- A `parameter` is the variable listed inside the parentheses in the function definition.\
- An `argument` is the actual value that is sent to the function when it is called.

## **Types of Function Arguments**

Python supports different types of arguments that can be passed during a function call.

**1. Default argument:**\
Default argument use a predefined value when no value is passed during the function call.

**2. Keyword Arguments:**\
Pass values using parameter names, so argument order does not matter.

**3. Positional Arguments:**\
Values are assigned to parameters based on their order in the function call.

**4. Arbitrary Arguments:**\
Allow functions to accept multiple values. This is done using two special symbols:

- *args collects extra positional arguments as a tuple.\
- **kwargs collects extra keyword arguments as a dictionary.
