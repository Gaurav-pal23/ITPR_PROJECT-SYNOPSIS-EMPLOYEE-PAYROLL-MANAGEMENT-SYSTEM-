# Employee Payroll Management System
A CLI based Application

## Introduction
The Employee Payroll Management System is a Java-based Maven project designed to
automate and simplify payroll processing in an organization. The system calculates
employee salaries based on predefined salary structure, attendance, tax deductions,
and bonuses.
This project is developed as an **project based on training** to demonstrate the practical
implementation of Core Java concepts, Maven project management, and basic business
logic used in payroll systems.

##  Objectives
The main objectives of this project are:
- To automate employee payroll calculation
- To reduce manual errors in salary processing
- To apply Object-Oriented Programming (OOP) concepts
- To understand Maven project structure and dependency management
- To simulate a real-world payroll workflow using a console-based application

## System Modules
1. Employee Management Module
- Manages employee details such as employee ID and basic salary
- Acts as the base entity for payroll processing

2. Attendance Management Module
- Takes employee attendance as input
- Applies salary deduction if attendance is below the defined threshold

 3. Payroll Calculation Module
- Calculates gross salary
- Applies tax and bonus
- Generates final net salary

 4. Reporting Module
- Displays payroll details in the form of a console-based payslip
- Helps in understanding salary breakup clearly

## Project Architecture
The project follows a modular and layered architecture:
- **Model Layer** – Represents core entities (Employee)
- **Service Layer** – Handles business logic (Payroll calculation)
- **Utility Layer** – Manages database connectivity (JDBC-ready)
- **Controller Layer** – Controls application flow (`Main.java`)
This structure improves readability, maintainability, and scalability.

## Technology Stack
| Technology | Description |
|----------|------------|
| Java | Core application logic |
| Maven | Project & dependency management |
| MySQL | Database (JDBC support included) |
| Eclipse IDE | Development environment |
| GitHub | Version control |

## Project Structure
EmployeePayrollSystem
├── pom.xml
└── src
└── main
└── java
├── db
│ └── DBConnection.java
├── model
│ └── Employee.java
├── service
│ └── PayrollCalculator.java
├── ui
│ └── MainMenu.java
└── Main.java

## How the System Works
1. The user runs the application
2. The system asks for basic salary and attendance
3. Salary components such as HRA, DA, TA, tax, and bonus are applied
4. Attendance-based deductions are calculated
5. Final net salary is displayed as a payslip

##  How to Run the Project
Prerequisites
- JDK 8 or higher
- Maven installed
- Eclipse IDE

Steps
1. Clone or download the repository
2. write code Maven Projec in Eclipse
3. Update Maven dependencies
4. Run `Main.java`
5. Enter salary and attendance details in the console

## Sample Output
Enter Basic Salary: 30000
Enter Present Days: 22

----- PAYSLIP -----
Net Salary = 34500

## Future Enhancements
- MySQL database integration for persistent storage
- Employee login system
- GUI-based interface using JavaFX or Swing
- Web-based payroll system using Spring Boot
- Advanced reporting and analytics

## Limitations
- Console-based interface
- Static salary components
- Single-user execution

## Bibliography
- Oracle Java Documentation
- Apache Maven Documentation
- MySQL Official Documentation
- GeeksforGeeks (Java)

##  Project Type
Academic Mini Project  
Maven-Based Java Application  
CLI Payroll Management System
