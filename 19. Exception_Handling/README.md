# Exception Handling

Exception Handling allows a program to handle unexpected errors during execution in a controlled way, instead of crashing abruptly. It enables programs to detect errors, manage them properly and continue execution wherever possible.

Handles runtime errors such as invalid input, file not found, division by zero and type mismatches that occur during program execution.
Helps improve program reliability by ensuring the application does not terminate unexpectedly when an error occurs.

**Syntax**
Python provides four main keywords for handling exceptions: try, except, else and finally each plays a unique role. 

```
try:
  # Code
except SomeException
  # Code
else:
  # Code
finally:
  # Code
```
- **try:** Runs the risky code that might cause an error.
- **except:** Catches and handles the error if one occurs.
- **else:** Executes only if no exception occurs in try.
- **finally:** Runs regardless of what happens useful for cleanup tasks like closing files.

## Key Objectives

### Built-in Exceptions

**1. BaseException**
This class is the root of Python's exception hierarchy. All other exceptions directly or indirectly inherit from it.

**2. Exception**
Exception class is the base for all non-exit exceptions. You will often catch Exception in general error-handling code when you are not targeting a specific error type.

**3. ArithmeticError**
ArithmeticError class is the base for all errors related to mathematical operations. You don’t usually raise it directly, but it provides a way to catch all math-related errors in one block.

**4. ZeroDivisionError**
ZeroDivisionError occurs when you attempt to divide a number by zero. Since division by zero is undefined in mathematics, Python raises this exception to signal the error.

**5. OverflowError**
OverflowError occurs when the result of a numerical operation is too large for Python to represent. While it handles large integers well, certain floating-point operations (like very large exponentials) can still cause this error.

**6. FloatingPointError**
FloatingPointError occurs when a floating-point calculation fails. By default, Python handles most floating-point issues silently (like dividing by zero results in inf or nan). However, you can explicitly enable floating-point error reporting with libraries like NumPy.

**7. AssertionError**
AssertionError is raised when the assert statement fails. The assert keyword is often used for debugging or testing assumptions in code.

**8. AttributeError**
AttributeError occurs when you try to access or assign an attribute that does not exist for an object.

**9. IndexError**
IndexError happens when you try to access a list (or any sequence) element with an index that is out of range.

**10. KeyError**
KeyError occurs when you try to access a dictionary key that doesn’t exist.

**11.	MemoryError**
MemoryError occurs when Python cannot allocate enough memory for an operation. This usually happens when trying to create extremely large data structures.

**12.	NameError**
NameError occurs when you use a variable or function name that has not been defined.

**Catching Exception**

We can handle errors more efficiently by specifying the types of exceptions we expect. This can make code both safer and easier to debug.

**1. Specific Exceptions**\
Catching specific exceptions makes code to respond to different exception types differently. It precisely makes your code safer and easier to debug. It avoids masking bugs by only reacting to the exact problems you expect.

**2. Multiple Exceptions**\
We can catch multiple exceptions in a single block if we need to handle them in the same way or we can separate them if different types of exceptions require different handling.

**3. Catch-All Handlers and their Risks**\
Catch-all handler is used to call to catch any exception (similar to else statement). Use only except keyword to define it.

**Raise an Exception**

We raise an exception using the raise keyword followed by an instance of the exception class that we want to trigger.

**Syntax:**

`raise ExceptionType("Error message")`
