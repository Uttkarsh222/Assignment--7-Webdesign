# Assignment--7-Webdesign

This assignment consists of two parts: a Login Page with form validations and a basic calculator functionality, and a Stopwatch Web Application.

Part A: Login Page and Basic Calculator
Description
The assignment involves creating a Login Page with form validations and implementing a basic calculator functionality on a Second Page.

Login Page
Functionality
Four input fields are provided: Email, User Name, Password, and Confirm Password, along with a Login button.
Validation rules are applied to each field:
Null checks
Special character check
Length checks (minimum and maximum length)
Email field only accepts northeastern email IDs
Error messages are displayed below each field in red color without using pop-ups.
The Login button is initially disabled and becomes enabled when all fields pass validation.
Upon successful validation, the user is redirected to the Second Page.
Second Page (Basic Calculator)
Functionality
The Second Page displays the logged-in UserName.
It contains two input fields labeled Number 1 and Number 2, and four buttons: Add, Subtract, Multiply, and Divide.
Upon clicking on any of the buttons, the result of the corresponding operation is displayed in a non-editable third field.
Validation rules are applied to the input fields:
Null checks
Special character check
Infinite value check
Error messages are displayed below each field without using pop-ups.
All validations are done using JQuery.
All four operations (Add, Subtract, Multiply, Divide) are performed using a single Arrow Function.
CSS
Basic CSS styling is applied to both pages for better presentation and readability.
Part B: Stopwatch Web Application
Description
The assignment involves designing a simple Stopwatch Web Application using Async, Await, Promises, Set Interval, and Clear Interval.

Stopwatch Web Application
Functionality
The Stopwatch Web Application is a single-page application consisting of a label displaying the current time in "HH:MM:SS" format, three buttons: Start, Stop, and Reset, and a date picker.
The label displaying time is not editable and initially set to "00:00:00".
The date picker displays the current date and allows selection of past and future dates without being editable.
On clicking the Start button, the time starts running. Clicking the Stop button pauses the time, and clicking the Reset button resets the time to "00:00:00".
CSS
Basic CSS styling is applied to the Stopwatch Web Application for better presentation and readability.
Technologies Used
HTML
CSS
JavaScript (JQuery for form validations, Stopwatch functionality, and Async/Await)
This assignment demonstrates the implementation of form validations, basic calculator functionality, and a Stopwatch Web Application using HTML, CSS, and JavaScript. JQuery is utilized for efficient form validation, and Async/Await is employed in the Stopwatch Web Application for handling asynchronous operations.