# # Constructors in Python: Welcome Message with Student Name

## 🎯 Aim
To write a Python program that creates a **Student** class with a **default constructor** and a method to display a welcome message along with the student’s name provided by the user.

## 🧠 Algorithm
1. **Get user input**: Accept the student's name from the user.
2. **Define the class**: Create a class `Student` with a default constructor (`__init__`).
3. **Default Constructor**: In the constructor, assign the user input (student name) to an instance variable `self.a`.
4. **Display Message**: Define a method `show` that prints "This is non-parameterized constructor" and a welcome message with the student’s name.
5. **Execute the Program**: Instantiate the `Student` class and call the `show` method.

## 🧾 Program

class Student: def init(self): self.name = ""

def display(self):
    print("Welcome", self.name)
name = input("Enter student name: ") s1 = Student() s1.name = name s1.display()
## Output
Enter student name: Harini Welcome Harini

## Result
The program executed successfully and displayed a welcome message using a Student class with a default constructor and a user-provided name.
