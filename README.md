# DVLD-Project
# DVLD - Driver & Vehicle Licensing Department System

A comprehensive desktop application designed to streamline and automate the operations of a **Driver and Vehicle Licensing Department**. This project was developed as a capstone project during my software engineering journey to demonstrate mastery of professional software architecture and database management.

---

##  Overview
The **DVLD System** handles the entire lifecycle of driving licenses, from the initial application and testing (Vision, Written, and Street) to issuance, renewal, and even managing violations and license detentions.

##  Architecture & Design
The project is built using the **3-Tier Architecture** pattern to ensure a clean separation of concerns:
* **Presentation Layer (UI):** Built with C# WinForms, focusing on a user-friendly and responsive interface.
* **Business Logic Layer (BLL):** Contains all the validation rules and core application logic.
* **Data Access Layer (DAL):** Manages all communications with the database using ADO.NET for high performance.

---

##  Key Features
* **People & User Management:** Centralized system to manage person data and system users with specific permissions.
* **Application Workflow:** Full management of local and international license applications.
* **Tests Management:** Integrated system for scheduling and managing test appointments (Vision, Written, Street).
* **License Operations:** Issuing, renewing, replacing (lost/damaged), and detaining/releasing licenses.
* **Security:** Password hashing and role-based access control.

##  Tech Stack
* **Language:** C#
* **Framework:** .NET Framework
* **Database:** Microsoft SQL Server
* **Data Access:** ADO.NET
* **UI:** Windows Forms (WinForms)

---

##  Project Structure
* `DVLD/`: The Presentation Layer (Forms, Resources).
* `DVLD_Business/`: The Business Logic Layer classes.
* `DVLD_DataAccess/`: The Data Access Layer and database helper classes.
* `Database/`: Contains SQL scripts to recreate the database schema and lookup data---

---
##  Core Concepts Applied
- **Object-Oriented Programming (OOP):** Inheritance, Encapsulation, and Polymorphism.
- **Relational Database Design:** Normalization, Relationships, and Stored Procedures.
- **Clean Code:** Following naming conventions and modularizing code for maintainability.

---
*Developed as part of the "Abu-Hadhoud" Programming Path.*
