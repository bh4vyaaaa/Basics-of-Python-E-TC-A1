# Experiment 2
## Bhavya Pandya
### E&TC A1
### PRN - 25070123139

Title 
Python Environment, Data Types, Operators, and Basic Input/Output

Aim
To study the Python programming environment and interface, understand execution modes, variables, data types, operators, and basic input/output operations in Python.
________________________________________
Objectives
•	To understand the Python programming environment and interface
•	To study Python execution modes
•	To understand comments in Python
•	To learn variables, identifier rules, and data types
•	To study different operators and expressions
•	To understand basic input and output mechanisms

1. The Python Environment
The Python environment consists of the essential tools and interfaces required to write, run, and debug code. Depending on your project's needs, you can choose from several different interfaces:

Python Shell: The most basic way to run code, ideal for quick tests.

Jupyter Notebook: A web-based tool that allows you to combine live code, equations, and visualizations.

Integrated Development Environments (IDEs): Comprehensive software like VS Code, PyCharm, or Spyder that offers advanced debugging and project management.

Cloud-Based Platforms: Tools like Google Colab that allow you to write and run Python in your browser with no setup required.

2. Modes of Execution
Python code is typically executed in one of two ways:

A. Interactive Mode
In this mode, the interpreter executes commands line-by-line.

Immediate Feedback: You see the results instantly after pressing enter.

Best For: Experimenting with new libraries, testing short snippets, or learning basic syntax.

Common Tools: Python Shell, Jupyter cells, and Google Colab.

B. Script Mode
In script mode, you write your entire program in a text file before running it.

Full Execution: The interpreter processes the file from start to finish as a single unit.

Best For: Building complex applications, automation scripts, and large-scale projects.

File Format: These files are saved with a .py extension.

3. Documenting Code with Comments
Comments are essential for explaining logic and making code readable. Since the Python interpreter ignores them during execution, they serve purely as notes for the programmer.

Single-line Comments: Created using the # symbol. Everything following it on that line is ignored.

Multi-line Comments: Often written using triple quotes (''' or """). While these are technically string literals, they are widely used for longer explanations or documentation.

4. Variables and Identifiers
A variable acts as a labeled container for storing data in your computer's memory. When naming these containers (identifiers), you must follow specific rules:

Starting Character: Must begin with a letter (A–Z, a–z) or an underscore (_).

No Digits at the Start: You cannot begin a variable name with a number.

Case Sensitivity: myVar and myvar are treated as two completely different variables.

Reserved Keywords: You cannot use names like if, else, or while as they are reserved for Python’s internal logic.

Note: Python features dynamic typing, which means you don't need to declare a variable's type (like int or string) beforehand; Python figures it out based on the value you assign.

5. Data Types in Python
Python provides several built-in data types to store different kinds of data.
Basic Data Types
•	Integer (int): Whole numbers
•	Floating-point (float): Decimal numbers
•	String (str): Sequence of characters
•	Boolean (bool): True or False
The data type of a variable can be identified using the type() function.

6. Operators and Expressions
Operators are symbols used to perform operations on variables and values.
Types of Operators
•	Arithmetic Operators: Used for mathematical calculations
(+, -, *, /, %)
•	Relational Operators: Used for comparison
(>, <, >=, <=, ==, !=)
•	Logical Operators: Used to combine conditions
(and, or, not)
•	Assignment Operators: Used to assign values
(=, +=, -=, *=, /=)
•	Bitwise Operators: Perform operations at bit level
(&, |, ^, <<, >>)
An expression is a combination of operators and operands that produces a result.

7. Basic Input and Output Operations
Input and output operations allow interaction between the user and the program.
•	Input:
input() function is used to accept input from the user.
Input is treated as a string by default and may require type conversion.
•	Output:
print() function is used to display output.
Formatted output can be achieved using commas or formatted strings.

Conclusion
Thus, the Python programming environment, execution modes, variables, data types, operators, and basic input/output operations were studied and understood.

Programs
1.	# Comments

# This is a single-line comment
# Program to demonstrate Python interface and comments
"""
This is a multi-line comment (docstring).
Python supports interactive and script modes.
"""
print("Welcome to Python Programming")
print("This program demonstrates comments and execution modes")

2.	# Variable declaration
student_name = "Snehal"
age = 45
height = 5.3
is_faculty = True

# Display data types
print("Name:", student_name, "Type:", type(student_name))
print("Age:", age, "Type:", type(age))
print("Height:", height, "Type:", type(height))
print("Faculty Status:", is_faculty, "Type:", type(is_faculty))





3.	Arithmetic, relational, logical, assignment, and bitwise operators
a = 10
b = 5

# Arithmetic Operators
print("Addition:", a + b)
print("Subtraction:", a - b)
print("Multiplication:", a * b)
print("Division:", a / b)

# Relational Operators
print("a > b:", a > b)
print("a == b:", a == b)

# Logical Operators
print("AND:", a > 5 and b > 2)
print("OR:", a > 20 or b > 2)
print("NOT:", not(a > b))

# Assignment Operators
c = a
c += b
print("Assignment Result:", c)

# Bitwise Operators
print("Bitwise AND:", a & b)
print("Bitwise OR:", a | b)




4.	Input and display formatted output using input() and print()

# Input from user
name = input("Enter your name: ")
marks = int(input("Enter your marks: "))

# Output using formatted print
print("Student Name:", name)
print("Marks Obtained:", marks)
