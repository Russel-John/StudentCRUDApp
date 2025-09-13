# StudentCRUDApp
## Run This Command to Sql Before Debugging

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
