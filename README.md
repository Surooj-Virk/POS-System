POS_APP.zip

This repository contains a ZIP archive named "POS_APP.zip", which includes the complete source code for a Point of Sale (POS) System developed using C# and WPF (Windows Presentation Foundation).

---

Contents of the ZIP

The ZIP file includes:

- "POS_APP/"
  - "UI/" – User Interfaces (XAML forms for sales, stock, login, dashboard, etc.)
  - "BL/" – Business Logic Layer
  - "DL/" – Data Access Layer using ADO.NET and SQL Server
  - "Models/" – Data models like "Item", "Category", "Order", "User"
  - "App.config" – Configuration file (with DB connection string)
  - "POS_DB.sql" – SQL script to create database and tables (if included)

---

How to Use the Application

1. Download the ZIP
   - Click on "POS_APP.zip" and download it.

2. Extract the contents
   - Right-click the ZIP file → "Extract All" or use any extraction tool.

3. Open in Visual Studio / VS Code
   - Open the "POS_APP" folder as a project.
   - Make sure ".NET Framework" (4.5 or above) is installed.

4. Setup the database
   - Open "POS_DB.sql" in SQL Server and execute it to create the database.
   - Update "App.config" with your database connection string.

5. Build and run the project
   - Run the project using Visual Studio.
   - The login window will appear.

---

Functional Flow – Steps Performed in This POS System

 1. User Login / Authentication
- Admin/Manager login with role-based access.
- Login credentials are verified from the database.

 2. Dashboard Access
- A user-friendly dashboard appears after login.
- Provides navigation to Sales, Inventory, Reports, and Settings.

 3. Category & Item Management
- Add/Edit/Delete Item Categories.
- Add/Edit/Delete Items with details like name, code, unit, purchase & sale price, quantity, etc.

 4. Customer Orders
- Select items to add to the cart.
- Automatically calculates total, tax, and discount.
- Records customer name, phone, and payment method.
- Places order and generates order ID.

 5. Stock Management
- Real-time update of stock on sale and return.
- Manual stock reconciliation with fields:
  - Opening Stock
  - Purchase
  - Return
  - Sale
  - Closing Stock

 6. Invoice Generation
- Printable invoice with customer and item details.
- Option to search and reprint invoices.

 7. Sales Reports
- Filter reports by date, customer, or item.
- View total sales, revenue, and profit.

 8. Settings and User Management
- Add/Edit/Delete users.
- Approve new users.
- Role-based access control (Admin, Cashier, etc.)

---

Technologies Used

- C# / WPF (.NET Framework)
- SQL Server
- ADO.NET for data access
- XAML for UI design

---

Author

Surooj Virk  
GitHub: [@Surooj-Virk](https://github.com/Surooj-Virk)

---

License

This project is for educational and internal use only. All rights reserved.

