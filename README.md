# GradeManager - Student & Teacher Portal

## Overview
This project is a web application built using C# Razor Pages, designed to facilitate interactions between students and teachers. It provides functionality for managing student data, teacher records, and course-related information.

## Features
- **Student Management**: Add, edit, and view student details.
- **Teacher Management**: Maintain teacher records and assignments.
- **Course Handling**: Manage course enrollment and assignments.
- **Authentication & Authorization**: Secure access control for students and teachers.
- **Responsive UI**: User-friendly interface for seamless navigation.

## Technologies Used
- **C# Razor Pages**
- **HTML, CSS**
- **Entity Framework Core (for database interactions)**
- **SQL Server (Database - External Connection Required)**
- **Bootstrap (for styling and responsiveness)**

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone <repository_url>
   ```
2. Navigate to the project folder:
   ```sh
   cd project-folder
   ```
3. Restore dependencies:
   ```sh
   dotnet restore
   ```
4. Install required NuGet packages (if not installed automatically):
   ```sh
   dotnet add package Microsoft.EntityFrameworkCore.SqlServer
   dotnet add package Microsoft.AspNetCore.Identity.EntityFrameworkCore
   ```
5. Configure the database connection by updating the connection string in `appsettings.json` to point to the external database.
6. Run the application:
   ```sh
   dotnet run
   ```

## Usage
- Navigate to `http://localhost:5000` (or configured port) in your browser.
- Log in with the appropriate user role (Student/Teacher).
- Access and manage relevant data based on user permissions.

## Future Enhancements
- Enhance UI with additional themes.


---
For any questions or contributions, feel free to contact me. @c1n0ptik
