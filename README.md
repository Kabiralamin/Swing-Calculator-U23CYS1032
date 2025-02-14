# Swing-Calculator-U23CYS1032

NAME: SULEIMAN AL-AMIN KABIR;
MATRIC NO: U23CYS1032 ;
LEVEL: 200LEVEL ;
DEPARTMENT:CYBER SECURITY ;

Description of the Code
This Java program is a graphical calculator application built using the javax.swing library. It provides a user-friendly interface for performing basic arithmetic operations such as addition, subtraction, multiplication, and division, along with additional functionalities like clearing the input, deleting the last character, and negating numbers. Below is a detailed description of the code, including its components, how it works, and what is needed to build it.

What is Needed to Build It
(1)Java Development Kit (JDK):

The program requires the JDK to compile and run the Java code.

Ensure you have Java installed on your system.

(2)Integrated Development Environment (IDE):

An IDE like IntelliJ IDEA, Eclipse, or any text editor (e.g., VS Code) can be used to write and run the code.

(3)Libraries:

The program uses Java's built-in libraries:

java.awt for basic GUI components and layout management.

java.awt.event for handling user interactions (e.g., button clicks).

javax.swing for creating the graphical user interface (e.g., buttons, text fields, panels).

How the Program Runs
(1)Initialization:

When the program starts, the Calculator constructor is called, which sets up the GUI components (e.g., buttons, text field, panel) and initializes the calculator's layout.

(2)User Interaction:

The user interacts with the calculator by clicking buttons:

Number Buttons (0-9): Append the clicked number to the text field.

Decimal Button: Adds a decimal point to the current number.

Operator Buttons (+, -, *, /): Store the first number and the selected operator, then clear the text field for the second number.

Equal Button (=): Perform the calculation based on the stored operator and display the result.

Clear Button (Clr): Clear the text field.

Delete Button (Del): Remove the last character from the text field.

Negate Button ((-)): Negate the current number in the text field.

(3)Calculation Logic:

When the equal button is clicked, the program retrieves the second number, performs the arithmetic operation (based on the stored operator), and displays the result in the text field.

(4)Display:

The text field at the top of the calculator displays the current input or result.

Components of the Program
(1)JFrame:

The main window of the calculator.

Set to a size of 420x550 pixels and uses absolute positioning (setLayout(null)).

(2)JTextField:

A text field at the top of the calculator to display the current input and result.

Non-editable and uses a custom font (Ink Free, bold, size 30).

(3)JButton:

Buttons for numbers (0-9) and functions (+, -, *, /, etc.).

Each button is styled with a custom font and has an action listener attached to handle clicks.

(4)JPanel:

A panel to organize the number and operator buttons in a 4x4 grid layout.

(5)Variables:

num1, num2, and result: Store the operands and result of calculations.

operator: Stores the current arithmetic operation (+, -, *, /).

(6)ActionListener:

The Calculator class implements the ActionListener interface to handle button clicks.

The actionPerformed method defines the behavior for each button click.

Key Features
(1)Basic Arithmetic Operations:

Supports addition, subtraction, multiplication, and division.

(2)Additional Functionalities:

Clear (Clr): Clears the text field.

Delete (Del): Removes the last character from the text field.

Negate ((-)): Negates the current number in the text field.

(3)User-Friendly Interface:

Buttons are organized in a grid layout for easy access.

The text field displays the current input or result clearly.

(4)Error Handling:

The program does not explicitly handle errors like division by zero or invalid inputs (e.g., multiple decimal points). This can be added as an improvement.

How to Run the Program
(1)Copy the code into a Java file (e.g., Calculator.java).

(2)Compile the code using the command:
javac Calculator.java

(3)Run the program using the command:
java Calculator

((4)The calculator window will appear, and you can start performing calculations.

Potential Improvements
(1)Error Handling:

Add checks for division by zero and invalid inputs (e.g., multiple decimal points).

(2)Keyboard Support:

Allow users to input numbers and operators using the keyboard.

(3)Memory Functionality:

Add memory buttons (e.g., M+, M-, MR) to store and recall values.

(4)UI Enhancements:

Use a more modern font and color scheme.

Add support for resizing the calculator window.

Conclusion
This program is a simple yet functional calculator built using Java's Swing library. It demonstrates the use of GUI components, event handling, and basic arithmetic operations. With some improvements, it can be made more robust and user-friendly.
