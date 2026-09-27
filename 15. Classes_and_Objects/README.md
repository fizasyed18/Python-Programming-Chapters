# Classes and Objects

## **Class**

A class is a user-defined template for creating objects. It bundles data and functions together, making it easier to manage and use them. When we create a new class, we define a new type of object. We can then create multiple instances of this object type.

## **Object**

An object is a specific instance of a class. It holds its own set of data (instance variables) and can invoke methods defined by its class. Multiple objects can be created from same class, each with its own unique attributes.

## **Constructors**

Constructors are special methods used to initialize objects when they are created from a class. Object creation and initialization are handled through the `__new__()` and `__init__()` methods. Constructors help assign initial values to object attributes and prepare objects for use.

When an object is created:\
- The `__new__()` method creates and returns a new instance of the class.
- The` __init__()` method initializes the newly created object.
- The object becomes ready for use.

**1.`__new__()` Method**\
This method is responsible for creating a new instance of a class. It allocates memory and returns the new object. It is called before __init__.
        
**2.`__init__()` Method**\
This method initializes the newly created instance and is commonly used as a constructor in Python. It is called immediately after the object is created by `__new__ `method and is responsible for initializing attributes of the instance.

**Types of Constructors**

**1. Default Constructor:** \
It does not take any parameters other than self. It initializes the object with default attribute values.

**2. Parameterized Constructor:** \
It accepts arguments to initialize the object's attributes with specific values.

## **Inheritance**

Inheritance is a fundamental concept in object-oriented programming (OOP) that allows a class (called a child or derived class) to inherit attributes and methods from another class (called a parent or base class).

## **super() Function**

super() function is used to call methods from a superclass following Python’s Method Resolution Order (MRO). In particular, it is commonly used in the child class's __init__() method to initialize inherited attributes. This way, the child class can leverage the functionality of the parent class.

**Method Overriding in Inheritance**\
Method overriding allows a child class to provide its own implementation of a method that already exists in the parent class. This enables customized behavior while still maintaining the inheritance relationship.
