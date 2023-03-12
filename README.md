# Elevatus
Automated Web Testing with Selenium and Python
Automate Elevatus signup page and job application processes. I used guerilla mail service for signup. In start I navigate to guerrilla mail page to get mail address and then I navigate to elevatus web page.

Getting Started
To get started with this Task, follow these steps:

Clone the repository to your local machine.
Install the required dependencies by running pip install -r requirements.txt in your terminal.
Download and install the latest version of Google Chrome web browser.
Download and install the corresponding version of ChromeDriver for your Chrome browser.
Open the config.py file and enter your GuerrillaMail email address and password.
Run the tests using pytest in your terminal. use this command in terminal in project dir -> pytest --html=report.html
Task Structure
The task consists of the following files and folders:

chromedriver_binary: a Python module that adds the ChromeDriver binary to the system path.
pages: a folder that contains Python modules representing the different pages of the website.
tests: a folder that contains the Python test modules.
README.md: a Markdown file that contains information about the project.
Pages
The pages folder contains Python modules representing the different pages of the website. Each module contains a PageObject class that represents the page and its elements. The PageObject class contains methods that interact with the page elements and perform actions such as filling out forms and clicking buttons.

The following pages are represented in the pages folder:

GuerrillaMailPage: represents the GuerrillaMail inbox page.
SignupFormPage: represents the signup form page of the website.
EmailInboxPage: represents the email inbox page of the GuerrillaMail website.
ApplyForAJob: represents the job application page of the website.
Tests
The tests folder contains Python test modules that test the website's signup and job application processes using Selenium. Each test module contains one or more test functions that perform specific tests on the website.

The following tests are included in the tests folder:

test_signup: tests the website's signup process by filling out the signup form with random data and verifying that the email address received a verification email.
test_applyForJob: tests the website's job application process by filling out the job application form with random data and verifying that the application was submitted successfully.
Conclusion
This project demonstrates how Selenium can be used to automate the testing of a website's signup and job application processes. By creating PageObjects and using them to interact with the website's elements, we can easily create robust and reliable automated tests.
