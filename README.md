# RentWise

The RentWise is a .NET Framework-based application designed to manage the rental of various products, including cars, furniture, TVs, refrigerators, air conditioners, and other similar items. This README file provides an overview of the system, its features, and instructions for installation and usage.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Features

1. **Product Management**: Easily add, update, and remove products from the rental inventory. Each product can have various attributes, such as brand, model, and price.

2. **Customer Management**: Keep track of customer information, including name, contact details, and rental history.

3. **Rental Management**: Record and manage rental transactions, including start and end dates, rental fees, and product details.

5. **Pricing and Billing**: Calculate rental fees based on product type, duration, and any additional services.

6. **User Authentication**: Secure user access with role-based authentication (admin, customer) to ensure data privacy.
   
8. **Customer Address Update**: Customers can easily update their contact information and address details to keep their profile current.

7. **New Product Request**: Customers have the ability to request new products that are not currently available in the inventory. This feature allows customers to submit product requests, which can be reviewed by the management for potential addition to the rental inventory.

## Prerequisites

Before installing the Rental Management System, ensure you have the following prerequisites:

- [Visual Studio](https://visualstudio.microsoft.com/): To open and run the project.

- [.NET Framework](https://dotnet.microsoft.com/): The application is built on .NET Framework, so ensure you have the necessary runtime and SDK installed.

- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads): You will need a SQL Server instance for database management.


## Installation

1. Clone the repository to your local machine using Git:

   ```bash
   git clone https://github.com/your-username/rental-management-system.git

2. Open the project in Visual Studio.

3. Set up the database:
  Create a SQL Server database.
  Modify the connection string in the appsettings.json file to point to your database.

4. Run the Entity Framework migrations to create the database schema:
   ```bash
   Update-Database

5. Build and run the application.

## Usage

1. **Admin Dashboard**: Log in as an admin to manage products, customers, and view reports.
  
2. **Customer Dashboard**: Customers can browse available products, rent items, and view their rental history.

## Contributing

If you'd like to contribute to the project, please follow these steps:

1. **Fork the repository.**

2. **Create a new branch for your feature or bug fix:**

   ```bash
   
   git checkout -b feature/your-feature-name


3. **Make your changes and commit them.**
  
5. **Push your branch to your forked repository**
   
   ```bash

   git push origin feature/your-feature-name


5. **Create a pull request on the original repository.**





