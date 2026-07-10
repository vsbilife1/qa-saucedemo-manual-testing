# Application Study – SauceDemo

## Document Information

| Field            | Value                    |
| ---------------- | ------------------------ |
| Project          | SauceDemo Manual Testing |
| Application      | SauceDemo                |
| Document Version | 1.0                      |
| Prepared By      | Your Name                |
| Document Type    | Application Study        |

---

## Objective

The objective of this document is to understand the functionality of the public SauceDemo application before preparing test planning, test scenarios, and detailed test cases.

---

## Application Overview

SauceDemo is a publicly available demo e-commerce web application. It allows users to log in, browse products, view product details, add or remove items from the shopping cart, complete the checkout process, and log out.

This application is suitable for practicing manual and automation testing because it contains multiple user workflows commonly found in web applications.

---

## Functional Areas Identified

The following functional areas were identified during application exploration:

1. User Authentication
2. Product Inventory
3. Product Sorting
4. Product Details
5. Shopping Cart
6. Checkout Information
7. Checkout Overview
8. Order Completion
9. Navigation Menu
10. Logout

---

## High-Level User Flow

```text
Login
   ↓
Inventory
   ↓
Product Details (Optional)
   ↓
Add Product(s) to Cart
   ↓
Shopping Cart
   ↓
Checkout Information
   ↓
Checkout Overview
   ↓
Finish Order
   ↓
Order Confirmation
```

---

## Testable Components

| Module          | Observation                                               |
| --------------- | --------------------------------------------------------- |
| Login           | User authentication using valid credentials.              |
| Inventory       | Displays available products with prices and descriptions. |
| Product Sorting | Products can be sorted using available sort options.      |
| Cart            | Supports adding and removing products.                    |
| Checkout        | Collects customer information before order completion.    |
| Overview        | Displays order summary before confirmation.               |
| Order Complete  | Confirms successful completion of the checkout process.   |
| Navigation      | Provides access to menu options including logout.         |

---

## Assumptions

* The application is publicly available for learning and testing purposes.
* This study is based only on observable functionality.
* No confidential or proprietary information has been used.

---

## Out of Scope

The following areas are not evaluated in this study:

* Backend implementation
* Database validation
* Source code
* Performance testing
* Security testing
* Internal APIs
* Third-party integrations

---

## Conclusion

The application provides sufficient functionality to create a complete manual testing portfolio, including requirement analysis, test planning, test scenarios, test cases, bug reports, RTM, and a test summary report.
