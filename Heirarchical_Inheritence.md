# Hierarchical Inheritance in Python

This Python project demonstrates **Hierarchical Inheritance** using a base class `Details` and two derived classes `Employee` and `Patient`. The program collects and displays details for both employees and patients.

## 🎯 Aim

To write a Python program that uses **Hierarchical Inheritance** to input and display **Employee** and **Patient** details.

## 📘 Description

- **Base Class:** `Details`
  - Stores common attributes: `name`, `age`
  - Provides methods: `getName()`, `getAge()`

- **Derived Class 1:** `Employee`
  - Inherits from `Details`
  - Adds: `employee_id`, `department`
  - Method: `getEmployeeDetails()`

- **Derived Class 2:** `Patient`
  - Inherits from `Details`
  - Adds: `patient_id`, `disease`
  - Method: `getPatientDetails()`

## 🧠 Algorithm

1. Create base class `Details` with common attributes.
2. Create `Employee` class extending `Details`, adding employee-specific data.
3. Create `Patient` class extending `Details`, adding patient-specific data.
4. Get user input for employee and patient data.
5. Display collected information using class methods.

## Program
class Person: def get_data(self): self.name = input("Enter name: ") self.age = int(input("Enter age: "))

def display(self):
    print("Name:", self.name)
    print("Age:", self.age)
class Employee(Person): def get_employee(self): self.get_data() self.emp_id = int(input("Enter Employee ID: ")) self.salary = int(input("Enter Salary: "))

def display_employee(self):
    self.display()
    print("Employee ID:", self.emp_id)
    print("Salary:", self.salary)
class Patient(Person): def get_patient(self): self.get_data() self.patient_id = int(input("Enter Patient ID: ")) self.disease = input("Enter Disease: ")

def display_patient(self):
    self.display()
    print("Patient ID:", self.patient_id)
    print("Disease:", self.disease)
print("Employee Details") e = Employee() e.get_employee() e.display_employee()

print("\nPatient Details") p = Patient() p.get_patient() p.display_patient()
## Sample Output
Employee Details Enter name: Ravi Enter age: 30 Enter Employee ID: 101 Enter Salary: 50000 Name: Ravi Age: 30 Employee ID: 101 Salary: 50000

Patient Details Enter name: Arun Enter age: 45 Enter Patient ID: 201 Enter Disease: Fever Name: Arun Age: 45 Patient ID: 201 Disease: Fever
