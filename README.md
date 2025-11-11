# Dotnet_202403103520008
CRUD Operation - Product Management
# 🛒 CRUD Operation Product Management 

## 📘 Overview

The **Online Product Management System** is a full-featured web application built with **ASP.NET Core MVC** that provides complete **CRUD (Create, Read, Update, Delete)** functionality for managing products. This project demonstrates modern web development practices, including Entity Framework Core for database operations, memory caching for performance optimization, and responsive UI design.

### 🎓 Academic Information

**Project Name:** CRUD Operation - Product Management  
**Course:** Web Technologies with .NET  

**Student Details:**
- **Name:** Dipak Patil  
- **Enrollment Number:** 202403103520008  
- **Division:** 5E  
- **Branch:** AMTICS (IT)  
- **Repository:** `Dotnet_202403103520008`

### 🎯 Project Objectives

This project aims to demonstrate:
- Complete implementation of CRUD operations using ASP.NET Core MVC
- Entity Framework Core integration with SQLite database for data persistence
- Memory caching implementation for improved application performance
- Responsive and user-friendly interface design using Bootstrap framework
- MVC architectural patterns and best practices in web development
- Asynchronous programming techniques for better scalability and user experience

---

## ✨ Features

### Core Functionality

| Feature | Description |
|---------|-------------|
| **Create Products** | Add new products with comprehensive details including name, category, price, and stock quantity. Form validation ensures data quality and prevents incomplete entries. |
| **Read Products** | View all products in a searchable, sortable table format. Real-time search functionality allows filtering by product name or category for quick access. |
| **Update Products** | Edit existing product information with pre-populated forms. All fields are editable and validated to maintain data integrity throughout updates. |
| **Delete Products** | Remove products from the system with a confirmation step to prevent accidental deletions. Safe removal ensures database consistency. |
| **Search & Filter** | Real-time search across product names and categories. Case-insensitive filtering provides instant results as you type in the search box. |
| **Status Management** | Toggle product active/inactive status with visual indicators. Green badges show active products for easy identification at a glance. |

### Advanced Features

**📊 Dashboard Analytics**

The dashboard provides comprehensive business insights with real-time metrics:

- **Total Products Count** - Displays the complete number of products in the entire system inventory
- **Active Products Monitoring** - Shows count of currently active and available products for sale
- **Total Inventory Value** - Automatically calculates cumulative value of all products (Price × Stock)
- **Category Distribution** - Tracks the number of unique product categories for portfolio diversity analysis

**💾 Memory Caching**

Implements intelligent caching mechanism for enhanced performance:

- Uses IMemoryCache interface for storing frequently accessed product data in memory
- Significantly reduces database queries by serving cached data for repeat requests
- Configurable cache expiration policies with default 10-minute timeout for data freshness
- Automatic cache invalidation when products are created, updated, or deleted
- Similar to shared preferences concept for temporary data storage optimization

**🔍 Advanced Search Capabilities**

Powerful search functionality for quick product discovery:

- Real-time filtering that updates results instantly as users type
- Searches across multiple fields including product name and category simultaneously
- Case-insensitive search ensures results regardless of letter casing
- Clean and intuitive search interface integrated into the product list view

**📱 Responsive Design**

Mobile-first approach ensuring excellent user experience across all devices:

- Bootstrap 5 framework provides adaptive layouts for desktop, tablet, and mobile screens
- Touch-friendly interface elements optimized for mobile interactions
- Responsive tables that adjust column visibility based on screen width
- Consistent user experience across different devices and browsers

**🎨 User Interface Excellence**

Clean and modern design focused on usability:

- Intuitive navigation with clear visual hierarchy and organized layout structure
- Color-coded status indicators (green for active) for instant product status recognition
- Action buttons with distinct colors (orange for Edit, red for Delete) for clear functionality
- Professional appearance using Bootstrap components and custom styling
- Smooth transitions and hover effects for enhanced user interaction feedback

---


### Main Dashboard View

The dashboard serves as the central hub displaying key business metrics and quick access to all operations:

**Summary Statistics Cards:**
- **Total Products:** 5 - Complete count of all products in the system
- **Active Products:** 5 - Number of currently active and available products  
- **Total Value:** ₹22,35,000 - Cumulative inventory value calculation
- **Categories:** 3 - Unique product categories (Electronics, Clothing, Books)

**CRUD Operation Cards:**

Four prominently displayed action cards provide one-click access to main functions:

- **Create (Green)** - Plus icon with "Add New Product" for creating new inventory items
- **Read (Blue)** - Clipboard icon with "View All Products" for browsing complete catalog
- **Update (Orange)** - Pencil icon with "Edit Product" for modifying existing information
- **Delete (Red)** - Trash icon with "Remove Product" for safely deleting items

The dashboard uses a clean, professional layout with clear visual separation between metrics and actions. Color-coded cards help users quickly identify and access the functionality they need.

### Product List View

Comprehensive table displaying all product information in an organized, scannable format:

**Table Structure:**

The product list features a well-designed data table with the following columns:

- **ID** - Sequential product identifier for technical reference
- **Name** - Product name (e.g., "Laptop Dell XPS 15", "Samsung Galaxy S23")
- **Category** - Classification (Electronics, Clothing, Books)
- **Price** - Listed in Indian Rupees with proper formatting (₹75,000, ₹45,000, ₹5,000, ₹500, ₹800)
- **Stock** - Available quantity (10, 25, 50, 100, 75 units)
- **Status** - Green "Active" badge showing current product availability
- **Actions** - Edit (orange button) and Delete (red button) for each product

**Search Functionality:**

A search box at the top allows users to filter products by typing product names or categories. The search placeholder reads "Search products by name or category..." and provides instant filtering results.

**Sample Products Displayed:**

1. Laptop Dell XPS 15 - Electronics - ₹75,000 - Stock: 10
2. Samsung Galaxy S23 - Electronics - ₹45,000 - Stock: 25
3. Nike Running Shoes - Clothing - ₹5,000 - Stock: 50
4. JavaScript: The Definitive Guide - Books - ₹500 - Stock: 100
5. Wireless Mouse - Electronics - ₹800 - Stock: 75

The blue header row clearly identifies each column, while alternating row colors enhance readability. Action buttons are consistently placed on the right side of each row for quick access to edit and delete operations.

---

## 🛠️ Technologies Used

### Backend Technologies

| Technology | Version | Purpose |
|------------|---------|---------|
| **ASP.NET Core MVC** | 8.0 | Primary web application framework for building the application |
| **C#** | 12.0 | Programming language for backend logic and business rules |
| **Entity Framework Core** | 8.0 | Object-Relational Mapping (ORM) tool for database operations |
| **SQLite** | Latest | Lightweight file-based database for data storage |
| **IMemoryCache** | Built-in | In-memory caching for performance optimization |

### Frontend Technologies

| Technology | Version | Purpose |
|------------|---------|---------|
| **Razor Views** | Latest | Server-side rendering engine for dynamic HTML generation |
| **HTML5** | Latest | Markup language for structuring web content |
| **CSS3** | Latest | Styling and visual presentation of the application |
| **Bootstrap** | 5.3 | Responsive CSS framework for mobile-first design |
| **JavaScript** | ES6+ | Client-side scripting for interactive features |

### Development Tools

- **Visual Studio 2022 / Visual Studio Code** - Integrated Development Environment (IDE)
- **Git** - Version control system for tracking code changes
- **NuGet** - Package manager for .NET dependencies
- **SQLite Browser** - Database management and visualization tool
- **Chrome DevTools** - Browser debugging and testing tools

### Key NuGet Packages

- **Microsoft.EntityFrameworkCore** - Core EF functionality for database operations
- **Microsoft.EntityFrameworkCore.Sqlite** - SQLite database provider for EF Core
- **Microsoft.EntityFrameworkCore.Tools** - Migration and scaffolding tools
- **Microsoft.AspNetCore.Mvc.Razor.RuntimeCompilation** - Runtime view compilation for development

---

## 📦 Installation Guide

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- ✅ **.NET SDK 8.0 or higher** - Download from [dotnet.microsoft.com](https://dotnet.microsoft.com/download)
- ✅ **Visual Studio 2022** or **Visual Studio Code** - Choose your preferred IDE
- ✅ **Git** - Version control system for cloning the repository
- ✅ **SQLite** (optional) - For viewing database contents directly

### Installation Steps

#### 1️⃣ Clone the Repository

Open your terminal or command prompt and run:
git clone https://github.com/dipakpatil77/Dotnet_202403103520008/
cd OnlineProductManagementSystem
