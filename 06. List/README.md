# List

Lists are used to store multiple items in a single variable and are ordered, changeable, and allow duplicate values. They are dynamic, resizable and capable of storing multiple data types.

- **Mutable:** list elements can be changed, updated, added, or removed after the list is created.
- **Ordered:** elements maintain the order in which they are inserted.
- **Index-based:** elements are accessed using their position, starting from index 0.

**Creating a List**

Lists can be created in several ways, such as using square brackets [], the list() constructor or by repeating elements.

## **Accessing Items**

Elements in a list are accessed using indexing. Python uses zero-based indexing, meaning a[0] represents the first element. Negative indexing is also supported, where -1 accesses the last element.

## **Add List Items**

Elements can be added to a list using the following methods:

**1. append()** -> Adds an element at the end of the list.

**2. insert()** -> Adds an element at a specific position.

**3. extend()** -> Adds multiple elements to the end of the list.

The extend() method does not have to append lists, you can add any iterable object (tuples, sets, dictionaries etc.).

## **Remove List Items**

Elements can be removed from a list using the following methods:

**1. remove()** -> Removes the first occurrence of an element.

**2. pop()** -> Removes the element at a specific index or the last element if no index is specified.

**3. del** -> Deletes an element at a specified index.

**4. clear()** -> removes all items.

## **List Methods**

| Method | Description |
|---|---|
| append() | Adds an element at the end of the list |
| clear()	| Removes all the elements from the list |
| copy() | Returns a copy of the list |
| count()	| Returns the number of elements with the specified value | 
| extend() | Add the elements of a list (or any iterable), to the end of the current list |
| index()	| Returns the index of the first element with the specified value |
| insert() | Adds an element at the specified position | 
| pop() | Removes the element at the specified position |
| remove() | Removes the item with the specified value |
| reverse() | Reverses the order of the list |
| sort() | Sorts the list |
