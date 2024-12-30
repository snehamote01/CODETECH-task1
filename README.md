# CODETECH-task1 
Name SNEHA MOTE 
Company CODETECH IT SOLUTION
Domain Python Programming
Duration dec to jan2024-2025
Key Features of the Program
User Input Handling:

The program prompts the user to enter two numbers and an operation.
It uses input() to accept values and checks for valid numeric input using try-except.
Operations Supported:

Addition (+)
Subtraction (-)
Multiplication (*)
Division (/)
Exit Option: Allows users to stop the program when they choose.
Error Handling:

If the user inputs invalid data (e.g., non-numeric values), it shows an error message and prompts again.
Division by zero is handled gracefully by checking if the second number is zero before performing the operation.
Loop for Continuous Use:

The program allows users to perform multiple calculations without restarting it.
It keeps running until the user selects the exit option.
Output Formatting:

Results are displayed with clear messages, making it user-friendly.
Steps of Execution
The program starts with a welcome message.
Users are prompted to enter two numbers.
Users choose one of the operations by entering a number (1-4) corresponding to the desired operation:
1: Addition
2: Subtraction
3: Multiplication
4: Division
The program performs the selected operation and displays the result.
If the user selects 5, the program exits.
If any invalid input is given (e.g., text instead of a number or an invalid operation), the program notifies the user and asks for correct input.
Programming Concepts Covered
Input and Output:

Use of input() to gather user data.
Use of print() to display results and messages.
Data Types and Conversion:

Conversion of string input to float for calculations.
Control Structures:

if-elif-else for operation selection.
while loop to allow repeated use of the calculator.
Error Handling:

try-except for catching invalid numeric input.
Modularity:

The code is organized in a function (calculator()), making it reusable and easy to understand.
Possible Enhancements
Advanced Operations:

Include operations like exponentiation, modulus, or square roots.
History Tracking:

Store a history of calculations and display them upon request.
User Interface:

Develop a graphical interface using libraries like Tkinter or PyQt.
Better Input Validation:

Restrict inputs to numeric values directly and improve user prompts.
Customization:

Allow users to set default values or perform chained calculations.
