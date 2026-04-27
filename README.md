# Cpp-calculator-using-inharitance
Simple C++ program that use the concept of inheritance and function overriding.It consist of two classes simple Performs basic arithmetic operations(addition,subtraction,multiplication,division). complex Extends the functionality of the base class by adding input validation.It only allows operations when both input values are greater than zero. 

This project is a simple calculator built in C++ using Object-Oriented Programming (OOP) concepts. It demonstrates:
Inheritance
Function overriding
Input validation

🏗️ Structure

🔹 Base Class: simple
Stores two integers a and b

Functions:

getinput() → Takes input from user
add() → Adds numbers
sub() → Subtracts numbers
mul() → Multiplies numbers
div() → Divides numbers

🔹 Derived Class: complex

Inherits from simple
Overrides all arithmetic functions
Adds validation:
If a <= 0 or b <= 0, shows "Invalid Input!"
Otherwise calls base class functions

⚙️ How It Works

User enters two values
Program checks if values are positive
If valid:
Performs all operations
If invalid:
Displays error message

▶️ Example Output

Enter the Value of A : 10

Enter the Value of B : 5

A + B = 15

A - B = 5

A * B = 50

A / B = 2

🚀 How to Run

Open the code in any C++ compiler (Dev-C++, VS Code, etc.)
Compile the program:
g++ program.cpp -o program
Run:
./program

🎯 Concepts Used

Classes and Objects
Inheritance
Function Overriding
Access Specifiers (protected, public)

📚 Purpose

This project is useful for beginners to understand how inheritance works in C++ and how derived classes can modify base class behavior.

👨‍💻 Author

Muhammad Mateen
