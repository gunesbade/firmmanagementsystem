# Firm Management System – Java Console Application
This is a Java console-based application developed for the second project of the CMPE343 course. It simulates a firm management system with role-based access control for managers and regular employees. The application follows object-oriented programming principles and integrates with a MySQL database via JDBC.

## Features

### General
- Console-based interface with colorful ASCII Art on login
- Role-based login (Manager, Engineer, Technician, Intern)
- Turkish character support in terminal
- MySQL integration using JDBC

### Regular Employee
- Roles: engineer, technician, intern
- View full personal information (profile and non-profile)
- Update profile data (password, phone number, email)
- Mandatory password change on first login
- Logout to return to login screen

### Manager
- View and update own profile
- View all employees or filter by role
- View specific employee by username
- Update employee non-profile data (name, surname, etc.)
- Hire employee (add to DB with default password)
- Fire employee (except self, allowed by other managers)
- Access algorithm comparison module
- Logout to return to login screen

### Algorithms Module
- Manager can run performance tests on sorting algorithms
- Input: random integers (-10,000 to 10,000), size 1,000–10,000
- Sorting algorithms implemented:
  - Radix Sort
  - Shell Sort
  - Heap Sort
  - Insertion Sort
- Output: execution time and sorted array

## Technologies Used
- Java
- Object-Oriented Programming (inheritance, abstraction, encapsulation, polymorphism)
- JDBC
- MySQL
- GitHub

## Setup
1. Clone this repository.
2. Open the project in your Java IDE.
3. Import the MySQL database using the provided `.sql` script.
4. Configure JDBC connection (username, password).
5. Run the main class in terminal (supports Turkish characters).
