# StudentCRUDApp

A simple Windows Forms application with **CRUD (Create, Read, Update, Delete)** functionality using C# and SQL Server.

---

## 📦 Requirements
- Visual Studio (with Windows Forms .NET Framework support)
- SQL Server / SQL Server Express
- SQL Server Management Studio (SSMS) 

---

## 🗄️ Database Setup

Before running the application, execute the following SQL commands:

```sql
CREATE DATABASE StudentDB;
GO

USE StudentDB;
GO

CREATE TABLE Students (
    StudentID INT PRIMARY KEY,
    FirstName VARCHAR(50),
    LastName VARCHAR(50),
    Age INT,
    Course VARCHAR(50)
);
