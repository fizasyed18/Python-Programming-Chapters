# Arrays

Array is a collection of elements stored at contiguous memory locations, used to hold multiple values of the same data type. Unlike Lists, which can store mixed types, arrays are homogeneous and require a typecode during initialization to define the data type.

**Create an Array**\
Array can be created by importing an array module. `array(data_type, value_list)` is used to create array with data type and value list specified in its arguments.

### **Adding Elements**

Elements can be added to an array using insert() to place a value at a specific index, or append() to add a value at the end.

### **Accessing Items**

Array elements are accessed using their index with square brackets [ ]. Each item has a position starting from 0 and the index must be an integer.

### **Removing Elements**

Elements can be removed using remove(), which deletes the first occurrence of a value or pop(), which removes and returns an element (last by default or a specific index if provided).

### **Slicing**

Slicing is used to access a specific range of elements from an array using index positions.

### **Searching Element**

In order to search an element in the array we use index() method. This function returns the index of the first occurrence of value mentioned in arguments.

### **Updating Elements**

In order to update an element in the array we simply reassign a new value to the desired index we want to update.

## **Operations on Array**

**1. Counting Elements:** We can use `count()` method to count given item in array.

**2. Reversing Elements:** In order to reverse elements of an array use `reverse` method.

**3. Extend Element:** `extend()` function is used to attach an item from iterable to the end of the array. This method is used to add an array of values to the end of a given or existing array.

## **Array Unpacking**

- **Unpacking with Asterisk (*) Operator**

Using the * operator for unpacking works similarly with arrays as it does with lists. This allows you to capture multiple values in the middle of an array.

- **Unpacking Nested Arrays**

Arrays in Python can also contain other arrays, allowing you to work with nested structures.

- **Unpacking Using Indexing and Slicing**

You can also slice an array and unpack the results. This can be particularly useful if you want to extract only specific parts of an array.
