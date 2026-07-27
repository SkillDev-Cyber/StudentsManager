# Student Manager

A console-based student management system built in C# (.NET). This project 
demonstrates core object-oriented programming concepts, in-memory data 
management, and clean console UI design.

## Features

- **Add, Edit, Delete, Find, and List** student records
- **Grade Management**: enter grades for 10 subjects per student with 
  input validation (0–20 range)
- **Automatic Average Calculation** for each student's grades
- **Input Validation** for National ID format and age
- **Colorized Console Interface** for a clearer, more readable user experience

## Tech Stack

- C# / .NET
- Console Application (top-level statements)

## Project Structure

StudentsManager/
├── Models/
│ └── Student.cs
├── Services/
│ └── StudentsRepository.cs
└── Program.cs

## Getting Started

```bash
git clone https://github.com/username/StudentsManager.git
cd StudentsManager
dotnet run
```
