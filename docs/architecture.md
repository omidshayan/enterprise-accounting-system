# System Architecture

## 1. Overview

The Enterprise Accounting & Business Management System is a modular, multi-company and multi-branch business management platform.

It is built using a custom PHP MVC architecture, JavaScript-based frontend components, and a centralized MySQL database.

The system combines financial management, accounting, inventory, sales, purchasing, human resources, and specialized business operations in one integrated application.

## 2. High-Level Architecture

| Layer | Technology | Responsibility |
|---|---|---|
| Backend | PHP | Application logic and business operations |
| Backend Architecture | Custom MVC | Application structure and separation of responsibilities |
| Frontend | JavaScript, jQuery | Interactive user interface |
| Page Navigation | Swup | Smooth page transitions and app-like navigation |
| Database | MySQL | Centralized data storage |
| Mobile Interface | PWA | Mobile access and app-like experience |

## 3. Backend Architecture

The backend is developed using a custom PHP MVC architecture.

The application follows a modular design, allowing individual business modules to be developed, maintained, and extended with minimal impact on unrelated parts of the system.

Key architectural characteristics:

- Custom-built MVC structure
- Modular application organization
- Extensible backend components
- Centralized business logic
- Support for multiple companies and branches

## 4. Database Architecture

The application uses MySQL as its database management system.

A centralized database architecture is used to manage information belonging to multiple companies and branches.

The system supports company-level and branch-level business operations within this shared database environment.

## 5. Business Modules

The platform includes the following major modules:

### Financial Management
- Accounting and financial documents
- Banking and cash management
- Customer and supplier accounts
- Financial reporting

### Business Operations
- Sales management
- Purchasing management
- Inventory management
- Jewelry and gold business management

### Human Resources
- Employee management
- Salary and payroll management
- Attendance management
- Employee-specific access permissions

### Reporting & Dashboards
- Business and financial reports
- Management dashboards
- Operational information and summaries

## 6. Multi-Company & Access Management

The application supports multiple companies and branches within a shared database architecture.

Its access management system allows permissions to be defined and configured for individual users or roles.

This provides flexibility when assigning responsibilities and controlling access to different parts of the application.

## 7. Frontend & User Experience

The frontend is built using JavaScript and jQuery, with Swup providing smooth page transitions.

The application uses a custom-designed user interface and offers six visual themes, including:

- Neumorphism
- Glassmorphism
- Claymorphism

Users can also customize the colors of different interface sections.

## 8. Progressive Web App

The platform includes a dedicated PWA experience for mobile users, particularly managers.

The mobile interface shares the application's visual design foundation while using mobile-specific layout adaptations.

These include:

- Mobile-oriented navigation buttons
- Simplified component layouts
- Removal of unnecessary desktop-oriented elements
- Responsive mobile interaction patterns
- Installable, app-like access through supported browsers

## 9. Product Maturity

The system is fully operational and currently used by customers.

Its modular architecture and broad business functionality make it suitable for continued development and expansion.