# MatrixOperations_Semester3_COAL
This project is based on Assembly Language, developed under Computer Organization and Assembly Language Course during Semester Three

A menu-driven **Matrix Operations Project written in Assembly Language** using the `Irvine32.inc` library.

This program performs basic matrix operations on two predefined 3x3 matrices, including transpose, addition, subtraction, multiplication, scalar multiplication, and determinant calculation.

## Features
- Display operation menu
- Transpose Matrix 1
- Add two matrices
- Subtract two matrices
- Multiply two matrices
- Perform scalar multiplication
- Calculate determinant
- Print resultant matrix on screen

## Technologies Used
- Assembly Language
- MASM Assembler
- Irvine32 Library
- Visual Studio / MASM setup

## Project File
```text
MatrixOperationsCoalProject.txt
Required Library

This project uses:
INCLUDE Irvine32.inc
So you must have the Irvine32 library configured properly in your MASM/Visual Studio environment.

Matrix Data
The program uses two 3x3 matrices:
Matrix 1:
1 2 3
4 5 6
7 8 9
Matrix 2:
9 8 7
6 5 4
3 2 1
Scalar value:
2
Available Operations
Choice	Operation
1	Transpose Matrix 1
2	Add Matrices
3	Multiply Matrices
4	Scalar Multiplication
5	Subtract Matrices
6	Determinant
Program Menu
Select an operation:
1. Transpose Matrix 1
2. Add Matrices
3. Multiply Matrices
4. Scalar Multiplication
5. Subtract Matrices
6. Determinant
Enter Choice:
How to Run
Requirements
MASM assembler
Irvine32 library
Visual Studio with MASM support
Steps
Create a new Assembly Language project.
Add the source code file.
Configure Irvine32 library paths.
Build the project.
Run the program.
Select an operation from the menu.


Main Procedures

main
Controls the program flow and takes user input from the menu.

DisplayMenu
Displays all available matrix operation choices.

TransposeMatrix
Calculates the transpose of Matrix 1.

AddMatrices
Adds Matrix 1 and Matrix 2 element by element.

SubtractMatrices
Subtracts Matrix 2 from Matrix 1 element by element.

MultiplyMatrices
Performs matrix multiplication logic.

ScalarMultiply
Multiplies Matrix 1 by the scalar value.

Determinant
Calculates determinant of Matrix 1.

PrintMatrix
Prints the resultant matrix on the screen.

Concepts Used
Assembly procedures
Registers
Loops
Conditional jumps
Arrays in assembly
Matrix traversal
Memory addressing
Stack operations
Irvine32 input/output procedures
Arithmetic operations
Menu-driven programming
Important Registers Used
Register	Purpose
EAX	Arithmetic operations and output
EBX	Matrix/result address or temporary value
ECX	Loop counter
EDX	Inner loop counter or string address
ESI	Source matrix pointer
EDI	Destination/result matrix pointer
Output

The program prints the resultant matrix after performing the selected operation.
