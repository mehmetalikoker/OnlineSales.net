# What's OnlineSales.net Project

This project encompasses all end-to-end processes required for e-commerce operations. It features a robust product and category structure, a customer-facing web application for seamless sales, and a comprehensive administrative panel designed for full control over product layouts and UI design.
***
🚀 Key Features
🛍️ Customer Storefront
Dynamic Product Catalog: Browse products organized by categories with real-time filtering.

Smart Shopping Cart: Add, remove, and update item quantities with instant feedback.

Order Tracking: User profile section to view order history and current status.

Responsive UI: Fully optimized for mobile, tablet, and desktop views.

***
⚙️ Management Panel (Admin Dashboard)
Inventory Control: Full CRUD operations for products, including stock tracking and image management.

Category Management: Organize the store layout with a dynamic category tree.

Order Processing: Manage incoming orders (Approve, Ship, or Cancel).

Sales Analytics: Track revenue and user activity through the dashboard.

***
🏗️ Technical Stack
Built with a focus on clean code and the MVC (Model-View-Controller) pattern for high maintainability.

Framework: ASP.NET Core 8.0 MVC

ORM: Entity Framework Core (Code First Approach)

Database: Microsoft SQL Server

Frontend: HTML5, CSS3, JavaScript (ES6+), Bootstrap 5

UI Libraries: Toastr.js (Notifications), SweetAlert2 (Dialogs)
***
🛠️ Getting Started
Follow these steps to run the project locally:
Clone the Repository:
- git clone https://github.com/mehmetalikoker/OnlineSales.net.git
- Database Configuration: Update the ConnectionStrings in appsettings.json with your SQL Server credentials.
- Run Migrations: Open the Package Manager Console and execute: PowerShell Update-Database
- Launch: Press F5 in Visual Studio or run dotnet run in the terminal.
