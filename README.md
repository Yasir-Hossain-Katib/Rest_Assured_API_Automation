# Automated API Testing with Rest Assured
## Project Description
This project demonstrates end-to-end API testing for the application hosted at Daily Finance. The testing includes core features such as user management and item management. The APIs were first inspected using the browser's Network tab and automated using Rest Assured, a popular library for API testing in Java.

The automation covers both positive and negative test scenarios to ensure the reliability and robustness of the APIs. The process was divided into two phases:

- Postman Collection: Creating and testing API requests for the required features.
- Automation with Rest Assured: Automating the same requests and validating responses programmatically.

## Prerequisites
Ensure the following tools and libraries are installed:

- Java JDK (version 8 or later)
- Maven (for dependency management)
- IntelliJ IDEA or any Java IDE of your choice
- Postman (to inspect and test API requests)
- Browser Developer Tools (to capture API details)

## What I Have Done
**Step 1: Inspecting APIs Using Postman**
Created a Postman collection for the following API endpoints:

- User Management APIs

  - Register a new user
  - Login as admin
  - Fetch the user list
  - Search for a user by ID
  - Edit user information (e.g., first name, phone number)
  - Login as any user

- Item Management APIs
  - Fetch the item list
  - Add a new item
  - Edit an item name
  - Delete an item

**Step 2: Automation Using Rest Assured**

- Automated the above API requests with necessary assertions.
- Handled positive cases to validate the functionality.
- Added negative cases to verify error handling, including:
  - Invalid input formats (e.g., missing fields during registration).
  - Unauthorized access (e.g., admin-only actions attempted by regular users).
  - Attempting to edit or delete non-existent items or users.
 
## How to Run the Tests
**Step 1: Clone the Repository**
Clone this project using: ```git clone <repository-url>```

**Step 2: Open the Project**
Open the project in IntelliJ IDEA or any Java IDE.

**Step 3: Run the Tests**
Execute the tests using TestNG:
  - Right-click on the src/test/java folder.
  - Select Run All Tests.

**Step 4: Analyze the Results**
The test results will show detailed logs and validations for each API request and response.

## Test Case

https://docs.google.com/spreadsheets/d/1J46yH8MItgMmvrAKKzzJ02qTye8Gbj70CHRdIvDZHNg/edit?usp=sharing

## Allure Report Screenshot

![image](https://github.com/user-attachments/assets/6079f00d-2ce5-4165-b4a6-4e29256a59d0)


![image](https://github.com/user-attachments/assets/1cf70ea1-9a15-4e72-adc3-456f19e979ec)
