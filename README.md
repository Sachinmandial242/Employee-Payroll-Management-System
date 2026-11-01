# Employee Payroll Management System

## 📌 Project Overview
The **Employee Payroll Management System** is a database management project developed using **PL/SQL in Oracle SQL Developer**.

The main purpose of this project is to manage employee information, salary details, and monthly payroll generation. It automatically calculates gross salary and net salary based on basic salary, allowances, bonus, and deductions.

## 🎯 Objectives
- To store and manage employee records.
- To maintain employee salary details.
- To calculate gross salary and net salary automatically.
- To generate monthly payroll records.
- To display employee-wise payroll reports.
- To reduce manual payroll calculation work.

## 🛠️ Technologies Used
- **Database:** Oracle Database
- **Language:** PL/SQL
- **IDE:** Oracle SQL Developer
- **Concepts:** Tables, Procedures, Functions, Triggers, Sequences, Cursors, Joins and Exception Handling.

## ⚙️ Project Features

1. **Employee Management:** Stores employee ID, name, department, designation, joining date and status.
2. **Salary Management:** Maintains basic salary, HRA, DA, bonus and deductions.
3. **Automatic Payroll ID:** Generates unique payroll IDs using a sequence and trigger.
4. **Salary Calculation:** Calculates gross salary and net salary automatically.
5. **Monthly Payroll Generation:** Generates payroll records for employees month-wise.
6. **Employee Deactivation:** Changes employee status from ACTIVE to INACTIVE.
7. **Payroll Report:** Displays monthly payroll information using a cursor.
8. **Exception Handling:** Handles duplicate employee IDs, duplicate payroll records and missing salary records.

## 🗂️ Database Tables

The project contains three main tables:

| Table Name | Description |
|---|---|
| EMPLOYEE | Stores employee information |
| SALARY | Stores employee salary details |
| PAYROLL | Stores monthly payroll records |

## 💻 PL/SQL Concepts Used

- CREATE TABLE
- PRIMARY KEY and FOREIGN KEY
- SEQUENCE
- TRIGGERS
- STORED PROCEDURES
- FUNCTIONS
- EXPLICIT CURSORS
- EXCEPTION HANDLING
- SQL JOINS
- COMMIT

## 🧮 Salary Calculation

**Gross Salary = Basic Salary + HRA + DA + Bonus**

**Net Salary = Gross Salary - Deduction**

## ▶️ How to Run the Project

1. Install and open Oracle SQL Developer.
2. Connect to your Oracle database.
3. Open the `PLSQLMiniProject.sqlnb` file.
4. Execute the SQL and PL/SQL statements in the correct order.
5. Enable DBMS Output to view procedure and cursor messages.
6. Check the EMPLOYEE, SALARY and PAYROLL tables.
7. Execute the final salary report query to view payroll details.

## 📊 Sample Data

The project contains five sample employees from different departments:

- Rahul Sharma – IT
- Aman Verma – HR
- Priya Singh – Finance
- Rohit Kumar – IT
- Neha Sharma – Sales

## 🚀 Future Scope

- Generate printable salary slips.
- Add employee login and authentication.
- Integrate a graphical user interface.
- Add monthly and yearly payroll summaries.
- Export payroll reports into PDF or Excel.

## 👨‍💻 Author

**Sachin Thakur**

## 📚 Project Type
Academic Mini Project – PL/SQL

**Developed using Oracle SQL Developer and PL/SQL.**
