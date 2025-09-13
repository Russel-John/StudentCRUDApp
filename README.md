# StudentCRUDApp
## Run This Command to Sql Before Debugging
-- Create the database
CREATE DATABASE StudentDB;
GO

-- Switch to the new database
USE StudentDB;
GO

-- Create the Students table
CREATE TABLE Students (
    StudentID INT PRIMARY KEY,  -- auto-increment handled by settings
    FirstName VARCHAR(50),
    LastName VARCHAR(50),
    Age INT,
    Course VARCHAR(50)
);
