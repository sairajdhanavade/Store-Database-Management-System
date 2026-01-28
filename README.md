# Store Database Management System (Part 1)

## 📌 Project Overview
This project involves designing and implementing a robust relational database for managing modern store operations. The primary goal is to move away from fragmented data storage toward a centralized system that improves reporting speed and inventory accuracy.

## 🎯 Business Objectives
*   **Centralized Record Keeping:** Manage store locations, employees, products, and customer data in one place.
*   **Inventory Management:** Track real-time stock levels across multiple branches.
*   **Sales Tracking:** Record customer orders and detailed order items for granular performance analysis.
*   **Data Integrity:** Ensure reliable data through foreign key relationships and schema constraints.

## 🛠️ Tech Stack
*   **Database:** SQL (PostgreSQL / MySQL / MS SQL Server)
*   **Design Tool:** Lucidchart / Draw.io (for ER Diagrams)
*   **Version Control:** Git & GitHub

## 📂 Database Schema (Part 1)
The system is built on a relational model consisting of the following core entities:
- **Stores:** Physical branch details.
- **Staff:** Employee information linked to specific stores.
- **Products:** Detailed catalog with categories and pricing.
- **Inventory:** Linking products to stores with quantity tracking.
- **Customers:** Profile data for sales attribution.
- **Orders & Order Items:** Detailed transaction records.

## 🚀 Key Features
- **Relational Integrity:** Implemented cascading deletes and specific constraints to prevent data orphans.
- **Optimized Queries:** Indexed key fields for faster retrieval of sales and stock reports.
- **Scalable Design:** Structured to handle multiple locations and high transaction volumes.

## 📈 Future Enhancements (Part 2)
- Advanced analytics for monthly revenue trends.
- Automated low-stock alerts.
- Integration with a front-end dashboard (e.g., Python/Flask or Power BI).
