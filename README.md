# Hotel_Management_System
The Hotel Management System is a Java-based desktop application designed to streamline and digitize hotel operations. Built using Java Fundamentals, Object-Oriented Programming (OOP), Java Swing for the GUI, and SQL Server as the backend database, this project offers an intuitive interface for both receptionists and managers to manage hotel operations effectively.

🧑‍💻 Technologies Used
Java Core: Used for implementing program logic and OOP principles

Java Swing: For building a graphical user interface (GUI)

SQL Server: For storing and retrieving data persistently

JDBC: Java Database Connectivity for communication between the app and database

🖥️ Application Structure
The system includes a Dashboard with two main roles:

1️⃣ Reception Panel
Accessible by hotel staff (no login required), this panel includes:

✅ Add New Customer

🛏️ Show Available and Unavailable Rooms

🧰 View Departments

👥 View All Employee Info

📋 View Customer Info

🧑‍💼 View Manager Info

🚪 Customer Check-out

🔍 Search Room by Type or Availability

🔄 Update Room Status (Available / Unavailable)

🚕 Pick-up Service Assignment

2️⃣ Manager Panel
Accessible via a Login System (Username & Password):

👨‍💼 Add New Employee

🚘 Add Driver Info

🏨 Add New Room Details

🔐 Authentication
A simple login system is implemented for Manager access using credentials stored in the database.

Reception-side functionalities are open to all staff.

🛠️ Database Integration
All data is stored securely in SQL Server.

Real-time data manipulation (insert/update/delete/search) via JDBC ensures accurate hotel operation tracking.

Tables include: customers, rooms, employees, drivers, departments, login, etc.
