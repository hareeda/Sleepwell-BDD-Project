Sleepwell BDD Automation Project
Overview
This project is a BDD (Behavior-Driven Development) automation framework developed using Selenium WebDriver, Cucumber, and TestNG for the Sleepwell website. The framework is designed to automate key user flows such as registration, warranty validation, showroom search, and customer support interactions.

Features
BDD-based test automation using Cucumber and Gherkin syntax.

Selenium WebDriver for UI automation.

TestNG for test execution and reporting.

Maven for dependency management and build automation.

Page Object Model (POM) for better maintainability.

Data-driven testing using Excel sheets.

ReportsManager for generating test execution reports.

Tech Stack
Programming Language: Java

Automation Framework: Selenium WebDriver

BDD Framework: Cucumber

Test Runner: TestNG

Build Tool: Maven

Dependency Management: pom.xml

Data Handling: Excel (Apache POI)

Reporting: Extent Reports

Test Scenarios Covered
Feature	Description	File
Callback Form	Automates the callback request process	CallBackForm.feature
Contact Us	Tests customer support form submission	ContactUsForm.feature
Find Showroom	Verifies showroom locator functionality	FindShowroom.feature
New Link	Validates the addition of new links	NewLink.feature
Offer Link	Tests promotional offers and discount links	OfferLink.feature
Server Error Handling	Checks application behavior for server errors	ServerError.feature
Warranty Link	Automates warranty claim and validation	WarrantyLink.feature
Warranty Registration	Ensures proper warranty registration flow	WarrantyRegistration.feature
Installation & Setup
Prerequisites
Java 8+ installed

Maven installed

ChromeDriver (or relevant WebDriver)

Git installed

Steps to Clone and Run
Clone the repository

git clone https://github.com/yourusername/sleepwell-bdd-project.git
cd sleepwell-bdd-project
Install dependencies

mvn clean install
Run tests using Maven

mvn test
Run tests using TestNG

Open CucumberRunner.java

Run as TestNG Test

Reporting
Test execution reports will be generated in the Reports/ directory.

Extent reports and logs are available in the test-output/ folder.

Contributing
Feel free to fork the repository and contribute by submitting pull requests!

