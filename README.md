# Internal Resource Booking System

This ASP.NET Core MVC web application was developed for the City of Joburg Junior Developer Assessment. The system helps employees view, book, and manage shared resources like meeting rooms, vehicles, and equipment, with built-in validation to prevent booking conflicts.

## Developer
**Ntando Bovungana**

## Tech Stack
- ASP.NET Core 8 (MVC)
- Entity Framework Core
- SQL Server Express / LocalDB
- Visual Studio 2022
- SQL Server Management Studio (SSMS)
- Bootstrap for styling

## Setup Instructions

### Getting Started
1. Open Visual Studio
2. Go to File > Open > Project/Solution
3. Select InternalResourceBookingSystem.sln

### Install Dependencies
If needed, restore NuGet packages:
- Open Tools > NuGet Package Manager > Package Manager Console
- Run: dotnet restore

### Database Setup
1. Check your database connection in appsettings.json:

"ConnectionStrings": {
  "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=ResourceBookingDV;Trusted_Connection=True;"
}

2. Apply migrations using Package Manager Console:
Run: Update-Database

### Running the App
Hit F5 or click the green play button. The application will launch in your browser.

### Login Credentials
- Username: admin
- Password: 1234

## What's Included

**Screenshots.zip** contains:
- Login page
- Homepage
- Add resource page
- View all resources
- Resource details
- Add booking page
- View bookings

**DatabaseBackup.zip** includes the .mdf and .ldf database files

## Submission Package
- **SourceCode.zip** - Complete project source code
- **Screenshots.zip** - Application screenshots
- **DatabaseBackup.zip** - Database backup files
- **README.md** - This setup guide

Files were uploaded via WeTransfer and submitted as per the assessment requirements.
