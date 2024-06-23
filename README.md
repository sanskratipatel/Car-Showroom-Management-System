# Car-Showroom-Management-System
# Car Showroom Management System

This project is a Car Showroom Management System developed in Java, utilizing Object-Oriented Programming (OOP) concepts such as classes, objects, inheritance, encapsulation, and polymorphism.

## Project Overview

The Car Showroom Management System allows managing cars, employees, and showrooms within a car dealership. It provides functionalities for adding new cars, managing employee details, and organizing showroom operations.

## Class Descriptions

### Car Class

The `Car` class represents a car object with attributes such as model, make, price, and year of manufacture.

- **Attributes**:
  - `String model`: Model of the car.
  - `String make`: Make or manufacturer of the car.
  - `double price`: Price of the car.
  - `int year`: Year of manufacture of the car.

- **Methods**:
  - `getDetails()`: Returns details of the car.
  - Other methods specific to operations on cars can be added as per requirements.

### Employee Class

The `Employee` class represents an employee working in the car showroom.

- **Attributes**:
  - `String name`: Name of the employee.
  - `int age`: Age of the employee.
  - `String designation`: Designation or role of the employee.
  - `double salary`: Salary of the employee.

- **Methods**:
  - `getDetails()`: Returns details of the employee.
  - Other methods related to employee management can be implemented.

### Showroom Class

The `Showroom` class represents a physical showroom where cars are displayed and managed.

- **Attributes**:
  - `ArrayList<Car> carsInShowroom`: List of cars currently available in the showroom.
  - `ArrayList<Employee> employees`: List of employees working in the showroom.

- **Methods**:
  - `addCar(Car car)`: Adds a new car to the showroom inventory.
  - `removeCar(Car car)`: Removes a car from the showroom inventory.
  - Other methods for managing showroom operations can be implemented.

### Main Class

The `Main` class serves as the entry point of the application and contains the `main` method.

- **Methods**:
  - `main(String[] args)`: Main method where the application execution starts. It initializes objects of `Car`, `Employee`, and `Showroom` classes, and demonstrates interactions between them.


## Usage

1. **Launch the application** to start managing your car showroom.
2. **Add new cars** to the showroom inventory.
3. **Manage employee details** and their roles within the showroom.
4. **Organize showroom operations** by adding or removing cars.


Thank you for using this Car Showroom Management System! We hope it helps you understand and implement OOP concepts effectively in Java.

