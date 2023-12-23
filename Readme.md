# Payroll System

This Java project implements a simple Payroll System using Object-Oriented Programming (OOP) concepts. It includes abstract classes, inheritance, polymorphism, encapsulation, and demonstrates the usage of a payroll system for both full-time and part-time employees.

## Project Overview

The project consists of the following classes:

1. **Employee (Abstract Class):**
   - Represents a generic employee with basic attributes like name and ID.
   - Contains an abstract method `calculateSalary()` to be implemented by subclasses.
   - Overrides `toString()` to provide a string representation of an employee, including calculated salary.

2. **FullTimeEmployee (Subclass of Employee):**
   - Represents a full-time employee with a fixed monthly salary.
   - Implements the abstract method `calculateSalary()` by returning the monthly salary.

3. **PartTimeEmployee (Subclass of Employee):**
   - Represents a part-time employee with the number of hours worked and hourly rate.
   - Implements the abstract method `calculateSalary()` by calculating the salary based on hours worked and hourly rate.

4. **PayrollSystem:**
   - Manages a list of employees and provides methods to add, remove, and display employee details.

5. **Main Class:**
   - Demonstrates the usage of the PayrollSystem by creating instances of FullTimeEmployee and PartTimeEmployee.
   - Adds employees to the payroll system, removes an employee, and displays the remaining employee details.

## Object-Oriented Concepts Used

- **Abstraction:**
  - The `Employee` class serves as an abstract representation of an employee, and its abstract method enforces implementation by subclasses.

- **Inheritance:**
  - The `FullTimeEmployee` and `PartTimeEmployee` classes inherit from the abstract `Employee` class, inheriting its attributes and behaviors.

- **Polymorphism:**
  - The `calculateSalary()` method is polymorphic, as its behavior differs based on the specific type of employee.

- **Encapsulation:**
  - Private attributes (`name`, `id`, `monthlySalary`, `hoursWorked`, `hourlyRate`) are encapsulated within their respective classes, accessed through public methods.

## Running the Project

1. Clone the repository: `git clone <repository-url>`
2. Open the project in your preferred IDE.
3. Run the `Main` class to see the functionality of the Payroll System.

Feel free to explore and modify the project as needed. If you have any questions or issues, please don't hesitate to reach out.

Happy coding!
