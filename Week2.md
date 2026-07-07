# Week 2 Notes

## toString()
- Converts an object into a readable string.
- Override toString() to print useful information.
- Without toString(), Java prints the object's memory address.

## equals()
- equals() compares the contents of two objects.
- == compares memory addresses.
- Override equals() when comparing objects.
- Override hashCode() whenever equals() is overridden.

## Deep Copy vs. Shallow Copy
- Shallow copy shares the same object reference.
- Deep copy creates a completely new copy.
- Deep copy protects encapsulation.

## Inheritance
- Inheritance lets one class reuse code from another class.
- Use the keyword `extends`.
- Parent class = Superclass
- Child class = Subclass

## this
- Refers to the current object.
- Used to access instance variables.
- Example:
  this.name = name;

## super
- Refers to the parent class.
- Used to call the parent constructor.
- Example:
  super(name);

## Polymorphism
- One object can have many forms.
- Example:
  Product p = new Book();
- Java chooses the correct method at runtime.

## Dynamic Binding
- Java decides which overridden method to use while the program is running.

## Abstract Classes
- Cannot be instantiated directly.
- Can contain abstract methods.
- Child classes must implement abstract methods.

## Abstract Methods
- Have no method body.
- Declared with the keyword abstract.
- Force child classes to provide an implementation.

## Static Variables
- Belong to the class, not an object.
- Shared by every object of the class.

## Static Methods
- Belong to the class.
- Can be called without creating an object.
- Example:
  Math.sqrt(25);

## Instance Variables
- Belong to one object.
- Every object has its own copy.

## Wrapper Classes
Primitive Type -> Wrapper Class

- int -> Integer
- double -> Double
- boolean -> Boolean
- char -> Character

## Boxing and Unboxing
- Boxing: Primitive -> Wrapper
- Unboxing: Wrapper -> Primitive
- Java performs this automatically.

## HashMap
- Stores key-value pairs.
- Keys must be unique.
- Useful methods:
  - put()
  - get()
  - size()
  - keySet()
  - values()
  - entrySet()

## Enhanced For Loop
Example:

for (String key : map.keySet())

- Goes through every item in a collection.

## instanceof
- Checks an object's type.
- Example:

if (object instanceof String)

## Math Class
Useful methods:
- Math.abs()
- Math.min()
- Math.max()
- Math.round()
- Math.ceil()
- Math.floor()
- Math.sqrt()
- Math.pow()

## Main Ideas
- Override toString() and equals() when needed.
- Use hashCode() with equals().
- Inheritance helps reuse code.
- Use this for the current object.
- Use super for the parent class.
- Static belongs to the class.
- Instance belongs to one object.
- HashMap stores key-value pairs.
- Polymorphism allows one object to have many forms.
- Abstract classes define common behavior for subclasses.
