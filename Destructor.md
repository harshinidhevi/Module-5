# Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## 🚀 Overview

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object is destroyed.

## 🧠 Algorithm

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program
class Demo: def init(self): print("Constructor called: Object created")

def __del__(self):
    print("Destructor called: Object destroyed")
obj = Demo() del obj

## 🧪 Output
Constructor called: Object created Destructor called: Object destroyed

## Result
The program executed successfully and demonstrated the working of a constructor and destructor in Python, where the constructor is called during object creation and the destructor is called when the object is deleted.
