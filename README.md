# Final Testing Project

This project demonstrates how to perform automated testing on front-end interfaces. It serves as an example of using multiple testing frameworks, including Cucumber, JUnit, and TestNG, to build a robust testing solution for web applications.

---

## Table of Contents
- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contact](#contact)

---

## About

This project is a practical implementation of front-end testing for web applications. It showcases the usage of multiple testing frameworks to validate the functionality of UI elements and ensure they meet specified requirements. It provides example test cases, scenarios written in Gherkin syntax, and integrations with tools like Selenium for browser automation. The main purpose is to demonstrate best practices for Behavior-Driven Development (BDD) using the following tools:

Cucumber: For writing test scenarios in plain English.
JUnit: For running unit and integration tests.
TestNG: For managing test configurations and execution.

---

## Features

Comprehensive testing of front-end UI functionalities, including:
Login and Registration Features: Validates correct behavior for login, registration, and logout flows.
Add to Shopping Cart: Ensures the shopping cart updates accurately when adding or removing items.
Reset Password Functionality: Tests the password recovery and reset features.
Integration of Cucumber with JUnit for Behavior-Driven Development (BDD).
Automatic generation of test reports (HTML format).
Cross-browser testing support via Selenium WebDriver.
Modular design for easy extension and maintenance.

---

## Installation

Follow the steps below to set up and run the project locally:

1)Clone the Repository:-
git clone [https://github.com/your-username/final-testing-project.git](https://github.com/Mohamedsaber45/Testing_Project.git)

2)Navigate to the Project Directory:-
cd final-testing-project

3)Open in IDE Open the project in IntelliJ IDEA or any Java IDE of your choice.

4)Install Dependencies Ensure you have Maven installed. Use the following command to download all dependencies:-
mvn install

5)Setup Drivers

Place the required browser drivers:-
(e.g., chromedriver.exe, geckodriver.exe, edgedriver.exe, firefoxdriver.exe) in the resources folder or in your system PATH.


---

## Usage

Running Tests:
1)To execute tests, use the following command in the terminal:
mvn test

2)Running Specific Tests
You can filter test execution using tags defined in your feature files. For example:
@CucumberOptions(
        features = "src/main/resources/features",
        glue = "StepDefinitions",
        tags = "@Login"
)

3)You can also run tagged tests directly via Maven:
mvn test -Dcucumber.filter.tags="@Login"

4)Viewing Test Reports:
After running tests, reports are automatically generated in the target/cucumber-reports folder. Open the HTML file to view detailed results.


---

## Contact

Name: Mohamed Saber Ahmed 
Email: mmms77990@gmail.com
GitHub: Mohamedsaber45
LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/mohamed-saber-18097a2a4?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BRE%2FrfWWkRfCdfLxHX14Wiw%3D%3D)
