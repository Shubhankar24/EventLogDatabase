# EventLoggerSystem

Welcome to **EventLoggerSystem** — a simple ASP.NET Core MVC application to log, view, and manage event logs efficiently. This project is built using the Code First approach with Entity Framework Core, offering manual CRUD operations without scaffolding, providing you full control over the code.

---

## Table of Contents

- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Getting Started](#getting-started)  
- [Project Structure](#project-structure)  
- [How to Run](#how-to-run)  
- [Usage](#usage)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Features

- Create, Read, Update, Delete (CRUD) operations for event logs  
- Manual controller and view implementations (no scaffolding)  
- Bootstrap-powered responsive UI with clean and modern design  
- Client-side validation using ASP.NET Core validation helpers  
- Easy to extend and customize  

---

## Technologies Used

- ASP.NET Core MVC  
- Entity Framework Core (Code First)  
- Bootstrap 5  
- C#  
- Visual Studio / VS Code  

---

## Getting Started

Follow these steps to get a local copy of the project running:

### Prerequisites

- [.NET 7 SDK](https://dotnet.microsoft.com/en-us/download) or later  
- IDE: [Visual Studio 2022](https://visualstudio.microsoft.com/) / [VS Code](https://code.visualstudio.com/)  
- SQL Server (LocalDB or any SQL Server instance)  

---

## Project Structure

```plaintext
EventLoggerSystem/
│
├── Controllers/
│   └── LogController.cs
│
├── Models/
│   └── Log.cs
│
├── Views/
│   ├── Logs/
│   │   ├── Index.cshtml
│   │   ├── Create.cshtml
│   │   ├── Edit.cshtml
│   │   ├── Details.cshtml
│   │   └── Delete.cshtml
│
├── Data/
│   └── EventLogDb.cs
│
├── appsettings.json
├── Program.cs
└── EventLoggerSystem.csproj
