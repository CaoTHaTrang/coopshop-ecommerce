# 🛒 CoopShop — E-Commerce & Convenience Store Management System

A web-based e-commerce and convenience store management system designed to support online shopping and store operations, including product management, order processing, inventory management, shipping, and customer interactions.

> **Project Context:** Academic team project, independently maintained and enhanced as a personal portfolio project.

---

## 📌 Overview

**CoopShop** is an e-commerce management system developed to simulate the core operations of a modern convenience store platform.

The system provides separate workflows for customers and administrators, covering product browsing, shopping cart management, order processing, shipping management, inventory operations, and system administration.

The project also provided practical experience in **system analysis, software testing, requirements analysis, and quality assurance**.

---

## ✨ Key Features

### 👤 Customer

* User registration and authentication
* Product browsing and searching
* Product detail viewing
* Shopping cart management
* Order placement
* Order tracking
* Product reviews and ratings

### 🛠️ Administration

* Product management
* Category management
* Inventory management
* Order management
* Customer management
* Shipping management
* User and system administration

### 🚚 Shipping Management

The shipping management workflow supports the processing and monitoring of delivery-related information throughout the order lifecycle.

Key activities include:

* Managing shipping information
* Updating shipping status
* Tracking delivery progress
* Validating shipping-related business rules
* Handling shipping workflow exceptions

---

## 🛠️ Technology Stack

| Category        | Technology                   |
| --------------- | ---------------------------- |
| Backend         | Laravel / PHP                |
| Frontend        | Blade, HTML, CSS, JavaScript |
| CSS Framework   | Tailwind CSS                 |
| Database        | MySQL                        |
| Package Manager | Composer, npm                |
| Build Tool      | Vite                         |
| Testing         | Functional / Manual Testing  |
| Version Control | Git & GitHub                 |

---

## 🏗️ System Architecture

The application follows a Laravel-based web application architecture.

```text
┌──────────────────────────┐
│          User            │
│ Customer / Administrator │
└────────────┬─────────────┘
             │
             ▼
┌──────────────────────────┐
│       Web Interface      │
│   Blade / Tailwind CSS   │
└────────────┬─────────────┘
             │
             ▼
┌──────────────────────────┐
│     Laravel Backend      │
│ Routes / Controllers     │
│ Models / Business Logic  │
└────────────┬─────────────┘
             │
             ▼
┌──────────────────────────┐
│         MySQL            │
│     Relational Data      │
└──────────────────────────┘
```

---

## 🧩 Main System Modules

The system is organized into several major functional modules:

* Authentication & User Management
* Product & Category Management
* Shopping Cart
* Order Management
* Inventory Management
* Shipping Management
* Customer Management
* Review & Rating
* Administration

---

## 🧪 Testing & Quality Assurance

Testing focused on validating the functional behavior of the system and ensuring that implemented workflows matched the expected business requirements.

### Shipping Management Testing

My primary testing responsibility focused on the **Shipping Management module**.

Testing activities included:

* Analyzing shipping-related requirements
* Designing test cases
* Preparing test scenarios
* Executing functional test cases
* Verifying expected and actual results
* Identifying and documenting defects
* Performing regression testing after fixes

---

## 🔍 System Analysis

In addition to testing, I contributed to **system analysis** activities throughout the project.

Key activities included:

* Analyzing functional requirements
* Understanding business workflows
* Identifying system actors and use cases
* Analyzing relationships between system modules
* Reviewing expected system behavior
* Supporting the definition of functional requirements

This experience helped bridge the gap between **business requirements and system implementation**.

---

## 👩‍💻 My Contributions

My primary responsibilities in the project were **System Analysis and Quality Assurance / Testing**.

### System Analysis

* Analyzed system requirements and business workflows.
* Contributed to functional analysis of major system modules.
* Reviewed system behavior against expected business requirements.
* Supported the analysis of system use cases and workflows.

### QA & Testing

* Designed and executed test cases for the Shipping Management module.
* Tested shipping workflows and business rules.
* Documented test results and identified functional defects.
* Verified defect fixes and performed regression testing.
* Contributed to overall system quality validation.

---

## 🚀 Getting Started

### Prerequisites

Make sure the following tools are installed:

* PHP
* Composer
* MySQL
* Node.js & npm
* Git

### Installation

Clone the repository:

```bash
git clone https://github.com/CaoTHaTrang/coopshop-ecommerce.git
cd coopshop-ecommerce
```

Install PHP dependencies:

```bash
composer install
```

Install frontend dependencies:

```bash
npm install
```

Create the environment file:

```bash
cp .env.example .env
```

Generate the Laravel application key:

```bash
php artisan key:generate
```

Configure the database connection in `.env`.

Run database migrations:

```bash
php artisan migrate
```

Start the Laravel development server:

```bash
php artisan serve
```

Run the frontend development server:

```bash
npm run dev
```

> Installation commands may vary depending on the local development environment and project configuration.

---

## 📸 Screenshots

Screenshots of the main application workflows will be added here.

Planned screenshots include:

* Homepage
* Product listing
* Product details
* Shopping cart
* Checkout
* Order management
* Shipping management
* Administration dashboard

---

## 🔮 Future Improvements

Potential improvements for future versions include:

* Online payment gateway integration
* Real-time order and shipping tracking
* Advanced inventory forecasting
* Improved search and filtering
* Automated testing
* Performance optimization
* Role-based access control improvements
* Deployment to a production environment

---

## 📚 Project Context

This project was originally developed as part of an academic team project.

The current repository is maintained as a **personal portfolio project**, with a focus on documenting and presenting my individual contributions in:

* System Analysis
* Software Testing
* Quality Assurance
* Shipping Management Testing

---

## 📄 License

This project is maintained for educational and portfolio purposes.
