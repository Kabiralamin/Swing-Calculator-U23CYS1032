# Swing-Calculator-U23CYS1032

NAME: SULEIMAN AL-AMIN KABIR;
MATRIC NO: U23CYS1032 ;
LEVEL: 200LEVEL ;
DEPARTMENT:CYBER SECURITY ;
Calculator README

Overview

This is a simple Java-based GUI Calculator built using Swing and AWT. It supports basic arithmetic operations such as addition, subtraction, multiplication, and division. The user interacts with the calculator through a graphical interface with buttons for numbers, operators, and additional functionalities like clearing, deleting, and negating numbers.

Features

	•	Basic Arithmetic Operations: Addition, Subtraction, Multiplication, and Division
	•	Decimal Support
	•	Negate Function: Convert a number to negative or positive
	•	Delete Function: Remove the last digit entered
	•	Clear Function: Reset the calculator

How It Works

1. User Interface (UI)

	•	The calculator’s interface is created using JFrame, JPanel, and JTextField.
	•	A JTextField displays the numbers and results, while JButtons handle user input.
	•	The buttons are arranged in a GridLayout for an intuitive design.

2. Number and Operator Buttons

	•	Numbers (0-9): When clicked, they append the digit to the JTextField.
	•	Operators (+, -, *, /): Stores the first number and the operator, then waits for the second number.
	•	Decimal (.): Allows input of decimal values.
	•	Equal (=): Performs the selected operation and displays the result.

3. Functionality

	•	Clear (Clr): Clears the entire input.
	•	Delete (Del): Removes the last digit entered.
	•	Negate (-/+): Converts the displayed number to negative or positive.

4. Action Handling

	•	The ActionListener interface handles button clicks.
	•	When an operator is clicked, the first number is stored, and the JTextField is cleared for the second number.
	•	On pressing =, the operation is executed, and the result is displayed.

How to Run the Calculator

Prerequisites

	•	Java Development Kit (JDK) installed on your system.

Steps to Run

	1.	Clone the Repository

git clone https://github.com/your-repo/calculator.git
cd calculator


	2.	Compile and Run

javac Calculator.java
java Calculator


	3.	The calculator GUI will launch, allowing you to perform calculations.

Future Enhancements

	•	Add advanced operations like square root, percentage, and power functions.
	•	Implement memory storage functionality.
	•	Improve UI with better styling and animations.

License

This project is open-source under the MIT License.

Enjoy using the calculator! Feel free to contribute to the project.
