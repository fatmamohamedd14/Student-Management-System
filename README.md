# 🎓 Student Management System – Windows Forms App

This is a desktop application built using **C# (.NET 9.0)** and **Entity Framework Core** to manage student records, grades, and academic reports.

## 📌 Features

- ➕ Add / ✏️ Edit / ❌ Delete student records  
- 🔍 Search by student ID  
- 🧾 Filter students by major  
- 📊 Generate student reports with grades  
- 💾 Data stored and retrieved from **SQL Server** via EF Core

## 🛠️ Technologies Used

- C# (Windows Forms)
- .NET 9.0
- Entity Framework Core
- SQL Server
- LINQ

## 🧩 Project Structure

- `Form1.cs`: Main interface
- `DisplayAllForm.cs`: View all students with options
- `SearchForm.cs`: Single student lookup
- `StudentReportForm.cs`: Generate detailed report
- `AppDbContext.cs`: EF Core DB context

## 💡 Highlights

- Implemented clean architecture using OOP and separation of concerns  
- Used `Include` / `ThenInclude` to load related data efficiently  
- Input validation and proper error handling with `try-catch`

## 📷 Screenshots

*Add here a screenshot of the main form, reports, or table display*

## 📦 How to Run

1. Clone the repository  
2. Open the solution in Visual Studio  
3. Set up your SQL Server connection in `AppDbContext`  
4. Run the application

---

🎯 This project was part of my training in database and desktop application development. It demonstrates my ability to build full-stack desktop apps with a focus on data integrity, user interface, and reporting.

