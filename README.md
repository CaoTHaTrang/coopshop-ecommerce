# 🛒 CoopShop — E-Commerce & Convenience Store Management System

## 🏷️ Project Information
| **Attribute** | **Details** |
| :--- | :--- |
| **Project Name** | CoopShop — Online Sales Management System |
| **Version** | v1.0.0 |
| **Academic Year** | 2024 - 2025 |
| **Status** | 🟢 Documentation & Testing Phase Completed |
| **Tech Stack** | Laravel (PHP), Nginx, Ubuntu Linux, MySQL |

---

### 🎯 1.1 Objective
The objective is to build **CoopShop**, a smart and user-friendly online convenience store platform. The system facilitates seamless product browsing, ordering, and online payments for customers, while providing a robust administrative dashboard for store managers to efficiently track inventory, fulfill orders, and monitor sales metrics.

### 🔍 1.2 System Scope & Integrations
* **In-Scope:** User account management (SMS OTP/Password), Shopping experience (search, cart management), Checkout workflows, Post-sales order tracking, and Admin operations (product, customer, and order management).
* **Out-of-Scope:** Load/Stress testing beyond baseline requirements, and internal testing of third-party systems.
* **Third-Party API Integrations:** Payment Gateways (VNPay, MoMo), Shipping/Logistics (GHN), and SMS OTP Services.

### 👥 1.3 User Roles & Permissions
| **Role** | **System Permissions & Capabilities** |
| :--- | :--- |
| **Customer** | Register/Login, search products, manage shopping cart, process payments, track/cancel orders, write reviews, and manage profile information. |
| **Administrator** | Full operational control: Manage product catalog (CRUD), monitor inventory levels, manage user accounts, confirm/update order statuses, view analytics, and assign Admin roles. |

---

## 🏗️ 2. Architecture & Technologies
CoopShop is built as a highly responsive Web Application, ensuring compatibility across all modern browsers (Chrome, Firefox, Safari, Edge) and devices (Desktop, Tablet, Mobile).

**Core Technology Stack:**
* **Server OS:** Linux (Ubuntu)
* **Web Server:** Nginx
* **Backend Framework:** Laravel (PHP)
* **Database:** MySQL
* **Design & QA Tools:** Figma (UI/UX), Jira (Agile/Bug Tracking), MS Office (Test cases, Planning).

---

## 🗄️ 3. Database Design

![Database ERD]([IMAGE PLACEHOLDER: Insert the Entity Relationship Diagram (ERD) from the System Analysis documentation])

The database architecture is designed to handle core e-commerce workflows efficiently:
* **Products & Inventory:** Manages SKUs, pricing, categorization, image assets, and stock statuses.
* **Customers & Orders:** Stores transaction histories, order statuses (Processing, Shipping, Delivered, Canceled), and contact information.
* **Payments & Shipping:** Manages discount vouchers, e-wallet links, and logistics tracking data.

---

## 🧪 4. Quality Assurance (QA) & Testing Process
A rigorous testing phase guarantees that all functional flows—from authentication to order completion—operate smoothly without critical defects.

**Testing Strategy & Levels:**
1. **Unit Testing:** Validates individual code components.
2. **Integration Testing:** Ensures stable communication with external APIs (VNPay, MoMo, GHN).
3. **System Testing:** End-to-end workflow verification on a Staging environment (Windows, MySQL).
4. **UAT (User Acceptance Testing):** Final validation to ensure the system is ready for end-users.

**Acceptance Criteria:**
* **100%** of defined Test Cases executed.
* Test Case Pass Rate of at least **95%**.
* **Zero (0)** Critical or Blocker bugs remaining.
* Maximum of 5 Medium priority bugs deferred.

---

---

---

## 📁 7. Project References & Documentation
* 📄 **CoopShop_Documentation**: Central repository for all project guidelines and specifications.
* 📄 **Information System Analysis & Design (Phân tích thiết kế HTTT.pdf)**: Detailed requirement specifications, Use Cases, Sequence/Class Diagrams, and UI/UX layouts.
* 📄 **Software Quality Assurance & Testing (Đảm bảo chất lượng và kiểm thử phần mềm.pdf)**: Comprehensive Test Plan, modular Test Cases, and Traceability Matrix.
* 🗄️ **coopshopdb.sql**: Database initialization script for schema creation and mock data seeding.
* 📄 **Database Management Systems (Hệ quản trị cơ sở dữ liệu.docx)**: Operation manual covering database architecture, infrastructure, and performance optimization.
