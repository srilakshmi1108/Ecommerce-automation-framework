# E-Commerce Automation Framework

## Overview
End-to-end test automation framework for e-commerce web application 
built using Selenium WebDriver, Java, TestNG with Page Object Model 
design pattern.

## Tech Stack
- Java
- Selenium WebDriver
- TestNG
- Page Object Model (POM)
- Maven
- JDBC (Database Validation)
- Extent Reports
- IntelliJ IDEA

## Test Scenarios Covered
| Module | Test Case | Status |
|---|---|---|
| Login | Valid login | ✅ Pass |
| Login | Invalid credentials | ✅ Pass |
| Login | Empty fields validation | ✅ Pass |
| Home Page | Product listing | ✅ Pass |
| Cart | Add product to cart | ✅ Pass |
| Cart | Remove product from cart | ✅ Pass |
| Checkout | Complete order flow | ✅ Pass |

## Framework Structure
```
src/test/java
├── pages          → Page Object Model classes
├── tests          → TestNG test classes
└── utils          → BaseClass and DB Connection
```

## How to Run
1. Clone the repository
2. Open in IntelliJ IDEA
3. Run `testng.xml` to execute all tests
4. View HTML report in `/reports` folder

## Key Features
- Page Object Model for maintainable code
- TestNG annotations for test management
- JDBC for database validation
- Extent Reports for detailed HTML reporting
- Maven for dependency management
