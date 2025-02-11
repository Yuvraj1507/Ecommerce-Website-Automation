# E-commerce Website Automation

📌 Project Overview

This project automates the testing of an E-commerce website using Selenium WebDriver with 
Java. The test cases cover various functionalities such as login, applying filters, 
adding products to the cart, checkout, and logout. It ensures seamless 
user experience and bug-free performance through automated testing.


# 🚀 Features & Functionalities

✅ Automated Functional Testing: Login, product filters, add-to-cart, checkout, and logout.

✅ Data-Driven Testing: Uses TestNG and SQL to validate dynamic test data.

✅ Cross-Browser Testing: Ensures compatibility across Chrome, Firefox, and Edge.

✅ Parallel Execution: Utilizes Selenium Grid to optimize test execution.

✅ CI/CD Integration: Configured with Jenkins for automated testing and reporting.

✅ Scalability: Built with Maven for dependency management.


# 🛠️ Technologies & Tools Used

* Programming Language: Java

* Automation Framework: Selenium WebDriver

* Test Framework: TestNG

* Build Tool: Maven

* Test Reporting: Extent Reports / Allure Reports

* Version Control: Git & GitHub

* CI/CD: Jenkins

* Database Validation: SQL

* Browser Testing: Selenium Grid


# 📂 Project Structure

# Ecommerce-Website-Automation-Java-Selenium/

│── src/
│   ├── test/java/
│   │   ├── LoginPage.java
│   │   ├── ApplyFilter.java
│   │   ├── AddToCart.java
│   │   ├── CheckoutPage.java
│   │   ├── LogoutPage.java
│── pom.xml (Maven dependencies)
│── README.md (Project Documentation)
│── testng.xml (TestNG Configuration)

# ⚙️ Installation & Setup
## Prerequisites
* Install Java JDK 8+

* Install Maven

* Install Selenium WebDriver

* Install TestNG Plugin (if using Eclipse/IntelliJ)

 ## Setup & Run Tests
1. Clone the repository:

git clone https://github.com/yourusername/Ecommerce-Website-Automation-Java-Selenium.git
cd Ecommerce-Website-Automation-Java-Selenium

2. Install dependencies using Maven:

mvn clean install

3. Run Test Cases:

mvn test

4. Generate Test Reports (Extent Reports / Allure Reports):

mvn allure:serve

## 📝 Test Cases Implemented

| **Test Case ID** | **Description** |
|-----------------|----------------|
| **TC01**        | Verify Login Functionality |
| **TC02**        | Apply Filter Functionality |
| **TC03**        | Add to Cart Functionality |
| **TC04**        | Checkout Process Verification |
| **TC05**        | Verify Logout Functionality |

## 🛠️ CI/CD Integration
* Configured Jenkins Pipeline for automated test execution.

* Integrated Allure Reports for detailed test reporting.

* Selenium Grid Setup for cross-browser testing.

# 🤝 Contribution Guidelines

1. Fork the repository.

2. Create a new branch:

git checkout -b feature-branch-name

3. Commit your changes:

git commit -m "Added new test cases"

4. Push to GitHub:

git push origin feature-branch-name

5. Create a Pull Request.


# 📜 License

This project is licensed under the MIT License.



