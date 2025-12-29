# Inventory Database Management System

A desktop Inventory Management System built using **Java Swing** for the frontend and **MySQL** for the backend. The system provides interactive management of products, users, invoices, and customers with dynamic table views and a modular GUI design.

---

## Features

- **User Management**: Authentication and authorization for multiple user types, tracking login activity.
- **Inventory Management**: Track products with stock levels, categories, and store associations.
- **Invoice Management**: Record detailed sales transactions including product, quantity, and price.
- **Provides Table**: Manages relationships between brands, stores, and discounts.
- **Interactive GUI**: Java Swing interface with tabbed panels for Products, Users, Invoices, and Customers.
- **Database Automation**: Executes multiple `.sql` scripts to create and populate relational database schema.
- **Extensible CRUD Functionality**: Framework for Create, Read, Update, Delete operations (some placeholders implemented).

---

## Tech Stack

- **Frontend**: Java Swing
- **Backend**: MySQL
- **Database Connectivity**: JDBC
- **Development Tools**: VSCODE / Eclipse, MySQL Workbench

---

## Database Schema

Core Tables:

1. **Inventory Users** – user authentication, authorization, and activity tracking.
2. **Product** – product details, stock levels, categories, store relationships.
3. **Invoice** – sales transactions with product, quantity, and net price.
4. **Provides** – relationship management between brands, stores, and discounts.
5. **Customers** – basic customer information.

---

## Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/gtaneja1/Inventory-Database-Management-
