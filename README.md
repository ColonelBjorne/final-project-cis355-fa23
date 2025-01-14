# CIS 355 Lab 2 

## Getting Started

### Initial Setup
Before you run the application, set up the database by following these steps. This ensures everything works smoothly.

### Prerequisites
- Open the project in VS Code and connect to the provided Dev Container. 

### Database Configuration
1. **Restore Dotnet Tools**: 
   Run `dotnet tools restore` in the terminal to install the Entity Framework (EF) CLI, necessary for applying EF migrations.

2. **Apply Database Migrations**: 
   Use `dotnet ef update` to apply all EF migrations and create the database if it doesn't exist.

### New Setup Feature
This release includes exciting new features. Follow the steps below to configure and use these features.
- Feature 1: Enhanced User Profiles
   1. Navigate to the user profile section after logging in
   2. Take advantage of the new profile customization options, including profile pictures and additional contact information

- Feature 2: Notification Center
   1. Access the Notification Center from the main dashboard
   2. Configure your notification preferenes for timely updates on system activities

- Feature 3: Export Data
   1. Explore the data export functionality under the "Data Management" section.
   2. Export relevant data sets in various formats to facilitate analysis and reporting.

### Running the Application
After setting up the database, start the application using `dotnet run` or through your IDE. It will automatically create a default admin account.

See the "Default Admin Account" section for more information on using this account.

## Default Admin Account

### Overview
A default admin account is created automatically on the first startup in a development environment. It's designed for immediate access to administrative features.

### Account Details
- **Username**: `admin`
- **Email**: `admin@admin.com`
- **Password**: `password`
- **Role**: `Admin`

### Usage
Use this account to sign in and access administrative areas. It's fully enabled for all features and settings, ideal for setup and testing.

### Troubleshooting
If you can't access the application with the admin account, check if the database has been seeded correctly and look for any startup errors in the application logs.
