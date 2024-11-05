# Automated-Testing-for-E-Commerce-Website

# Project Overview
The goal of this project is to automate the functional testing of a web-based eCommerce platform. The automation script was built using Selenium WebDriver with Java and simulates a complete user journey from login through product search, add-to-cart, and checkout, ultimately verifying the order confirmation message. The script mimics real-world user interactions, helping ensure critical features work as expected and offering a fast, reliable way to perform regression testing.
# Project Aim
To create an automated test suite that:
1.	Validates key functionalities (login, search, add to cart, checkout) on an eCommerce site.
2.	Ensures reliable execution for different user journeys.
3.	Reduces manual testing time, enhancing the efficiency and accuracy of testing processes.
________________________________________
# Scope and Purpose of the Project
The primary purpose of the project is to support the quality assurance process by:
•	Providing an automated testing tool that runs faster and more consistently than manual tests.
•	Identifying issues early in the development cycle to improve user experience.
•	Enabling end-to-end regression testing to ensure no critical functionality is broken after updates.
The project demonstrates proficiency in web automation and test scripting, delivering reliable and reusable test scripts suitable for use in continuous integration (CI) environments.
________________________________________
# Role in the Project
As the developer of this automated testing solution, I was responsible for:
1.	Designing the Test Flow: Mapping out user actions and creating a structured script that includes login, product search, add-to-cart, and checkout processes.
2.	Writing the Automation Script: Utilizing Selenium WebDriver and Java for test scripting.
3.	Element Identification: Using various element locators like XPath and CSS Selectors for precise element targeting.
4.	Error Handling and Synchronization: Incorporating implicit and explicit waits to handle dynamic web elements, ensuring synchronization.
5.	Validation of Results: Using assertions to verify successful login, item addition, and order placement messages.
6.	Testing and Debugging: Identifying and fixing issues in the script to improve reliability and reduce false negatives.
________________________________________
# Project Flow (End-to-End)
1.	Open Website and Setup
o	Open the Chrome browser.
o	Maximize the window and set an implicit wait for elements.
2.	Navigate to Login and Authenticate
o	Open the login page and input email and password.
o	Verify successful login by checking for an account link in the UI.
3.	Search and Add Product to Cart
o	Perform a search for "mac" and select "MacBook Pro" from results.
o	Update the quantity to 2 and add the product to the cart.
o	Verify successful addition by checking the confirmation message.
4.	Checkout Process
o	Open the shopping cart and proceed through each step of checkout.
o	Confirm the order by clicking the final confirmation button.
o	Validate the order by checking for the "Your order has been placed!" message.
5.	Close Browser
o	Close the browser to complete the testing process.
________________________________________
# Result of the Project
The automation script successfully:
•	Logs into the eCommerce site.
•	Searches and adds a product to the cart.
•	Proceeds through all checkout steps, confirming the order placement.
•	Validates success messages, ensuring a positive test outcome.
The project provides a reusable, scalable script for end-to-end testing of critical user flows, helping reduce manual testing time by 60-70% while improving testing accuracy and reliability.
________________________________________
# Skills and Technologies Used
1.	Programming Language: Java
2.	Automation Framework: Selenium WebDriver
3.	Test Structure: Java’s main method for executable tests
4.	Web Element Locators: XPath, CSS Selectors, id, name, and linkText
5.	Synchronization: Implicit waits, Explicit waits (WebDriverWait)
6.	Error Handling: Basic exception handling with try-catch for reliable script execution
7.	Browser Control: ChromeDriver for browser automation
8.	Testing Concepts: End-to-end testing, functional testing, regression testing
________________________________________
# Potential for Improvement
•	Integrating with TestNG or JUnit: For test suite management, data-driven testing, and better assertion handling.
•	Implementing Page Object Model (POM): To improve maintainability by separating the web page and test logic.
•	CI/CD Integration: Integrating the script with a CI/CD tool (e.g., Jenkins) for continuous testing.
________________________________________
# Automated End-to-End Testing of eCommerce Platform
•	Description: Developed an automation test script in Java using Selenium WebDriver to verify critical functionalities of an eCommerce platform, from login to checkout.
•	Responsibilities:
o	Designed and implemented the automation flow covering login, search, add-to-cart, and checkout.
o	Utilized XPath, CSS Selectors, and WebDriverWait for precise element handling and synchronization.
o	Integrated assertions to validate success messages and ensure test accuracy.
# Skills: 
Selenium WebDriver, Java, XPath, CSS Selectors, End-to-End Testing, Functional Testing, Automation

