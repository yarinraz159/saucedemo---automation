# saucedemo-Test-automation
# Test Automation Framework

This repository contains test automation code for a web application using Selenium WebDriver and Java, and including TestNG.

## Prerequisites

- Java Development Kit (JDK)
- Selenium WebDriver
- ChromeDriver

## Getting Started

1. Install the Java Development Kit (JDK) on your system.
2. Download and configure ChromeDriver for your operating system.
3. Clone this repository to your local machine.

## Project Structure

The project structure is organized as follows:

- `src/`: Contains the source code files.
- `pageObject/`: Contains the page object classes.
- `tests/`: Contains the test classes.
- `README.md`: Provides an overview of the project and instructions.

## Running the Tests

1. Open the project in an Integrated Development Environment (IDE) of your choice.
2. Configure the Selenium WebDriver and ChromeDriver paths in the test classes if required.
3. Run the desired test class by executing its `main` method.

## Test Classes

### BuyProductsTest

This test class performs a scenario where the user logs in, adds products to the cart, goes through the checkout process, and completes the purchase.

### BuyProductsTest2

This test class performs a scenario where the user logs in, adds products to the cart directly from the products page, goes through the checkout process, and completes the purchase.

### LoginTest

This test class performs a scenario where the user logs into the application.

### RemoveFromCartTest

This test class performs a scenario where the user logs in, adds products to the cart, and removes a specific product from the cart.

**> Note:** The framework assumes that the saucedemo web application is accessible at the URL "https://www.saucedemo.com/". Make sure the application is running and accessible before running the tests.

Make sure to update the ChromeDriver path according to your system configuration.

Feel free to explore the provided test classes and page objects to understand how the framework works and extend it further based on your specific requirements.

