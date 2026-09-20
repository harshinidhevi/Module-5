# Arithmetic Operations Using Multiple Inheritance in Python

This Python program demonstrates **multiple inheritance** by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes.

## 🎯 Aim

To write a Python program to calculate **Add, Sub & Division** using **Multiple Inheritance**.

## 🧠 Algorithm

1. **Define `Calculation1` class**
   - Contains `Summation(a, b)` method to return the sum of two numbers.
2. **Define `Calculation2` class**
   - Contains `Subtraction(a, b)` method to return the difference of two numbers.
3. **Define `Derived` class**
   - Inherits from both `Calculation1` and `Calculation2`.
   - Contains `Division(a, b)` method to return the division result.
4. **Input**
   - Prompt the user to enter two numbers.
5. **Process**
   - Create an object of the `Derived` class.
   - Call `Summation`, `Subtraction`, and `Division` methods.
6. **Output**
   - Display the results of the three operations.

## 💻 Program 
class Addition: def add(self, a, b): return a + b class Subtraction: def sub(self, a, b): return a - b class Division: def div(self, a, b): if b != 0: return a / b else: return "Cannot divide by zero" class Calculator(Addition, Subtraction, Division): pass

a = float(input("Enter first number: ")) b = float(input("Enter second number: "))

obj = Calculator()

print("Addition:", obj.add(a, b)) print("Subtraction:", obj.sub(a, b)) print("Division:", obj.div(a, b))
## Output Example

Enter first number: 10 Enter second number: 5 Addition: 15.0 Subtraction: 5.0 Division: 2.0
