# Sets

Sets are used to store multiple items in a single variable. Set items are unordered, unchangeable, and do not allow duplicate values.

- **Unordered**\
Unordered means that the items in a set do not have a defined order.

- **Unchangeable**\
Set items are unchangeable, meaning that we cannot change the items after the set has been created.

- **Duplicates Not Allowed**\
Sets cannot have two items with the same value.

## **Type Casting**

`set()` method is used to convert other data types, such as lists or tuples, into sets.

## **Join Sets**

There are several ways to join two or more sets in Python.

- The `union()` and `update()` methods joins all items from both sets.

- The `intersection()` method keeps ONLY the duplicates.

- The `difference()` method keeps the items from the first set that are not in the other set(s).

- The `symmetric_difference()` method keeps all items EXCEPT the duplicates.

**1. Union** -> The union() method returns a new set with all items from both sets.\
**2. Update** -> The update() method inserts all items from one set into another.\
**3. Intersection** -> The intersection() method will return a new set, that only contains the items that are present in both sets.\
**4. Difference** -> The difference() method will return a new set that will contain only the items from the first set that are not present in the other set.\
**5. Symmetrical Difference** -> The symmetric_difference() method will keep only the elements that are NOT present in both sets.

## **Frozenset**

Frozenset is an immutable version of a set. Its elements cannot be changed after creation, but you can perform operations like union, intersection and difference.

## **Set Methods**

|Method|Description|
|---|---|
| add() | Adds an element to the set |
| clear() | Removes all the elements from the set |
| copy() | Returns a copy of the set |
| difference()	| Returns a set containing the difference between two or more sets |
| difference_update()	|	Removes the items in this set that are also included in another, specified set |
| discard()	|	Remove the specified item |
| intersection()	|	Returns a set, that is the intersection of two other sets |
| intersection_update()	|	Removes the items in this set that are not present in other, specified set(s) |
| isdisjoint()	|	Returns True if NO items of this set is present in another set |
| issubset()	|	Returns True if all items of this set is present in another set, Returns True if all items of this set is present in another, larger set |
| issuperset()	|	Returns True if all items of another set is present in this set,	Returns True if all items of another, smaller set is present in this set |
| pop()	|	Removes an element from the set |
| remove()	|	Removes the specified element |
| symmetric_difference()	|	Returns a set with the symmetric differences of two sets |
| symmetric_difference_update()	|	Inserts the symmetric differences from this set and another |
| union()	|	Return a set containing the union of sets |
| update()	|	Update the set with the union of this set and others |
