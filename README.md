# WinFormsStoreApp

## 📌 About

**WinFormsStoreApp** is a Windows Forms desktop application for managing a flower and gift store.

> ⚠️ **Note:** This is an older project I wrote during my early university days while learning desktop application development. The code reflects my learning process at that time.



## 🖥 Features

* Dashboard with sales overview
* Add, edit, and remove cashiers
* Add, edit, and remove products
* Sales reports
* Login system with basic authentication
* Data displayed in tables using `DataGridView`



## 🖼 Screenshots



| Login                           | Dashboard                               | Sales Reports                                  |
| ------------------------------- | --------------------------------------- | ---------------------------------------------- |
| ![Login](screenshots/login.png) | ![Dashboard](screenshots/dashboard.png) | ![Sales Reports](screenshots/sales_report.png) |
| Add Cashier                                 | Add Products                                  | Cashier's Portal                                      |
|  |  | |
| ![Add Cashier](screenshots/add_cashier.png) | ![Add Products](screenshots/add_products.png) | ![Cashier's Portal](screenshots/cashier's_portal.png) |






## ⚙️ Project Structure (Main Forms)

* `Form1.cs` – Dashboard
* `Form2.cs` – Sales Reports
* `Form3.cs` – Login
* `Form4.cs` – POS / Order Management
* `Form5.cs` – Cashier Management
* `Form6.cs` – Product Management



## 🛠 Technologies

* C#
* Windows Forms (.NET Framework)
* Entity Framework (Database connection)
* SQL Server / LocalDB



## 🔧 Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/RinadSalem/WinFormsStoreApp.git
   ```
2. Open the solution in Visual Studio.
3. Restore NuGet packages if needed.
4. Build and run the project.



## 📝 Notes

* This project was developed as part of a **university course** on mobile/desktop application development.
* Some parts of the code (like hard-coded data) were written for learning purposes.
* `.gitignore` should exclude: `bin/`, `obj/`, `*.user`, `.vs/`, and database files (`.mdf`, `.ldf`) if you don’t want them on GitHub.
* Screenshots folder should be included for README visuals.
