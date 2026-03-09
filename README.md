# RPN Calculator

This repository contains an **RPN (Reverse Polish Notation)** calculator implemented in **C**. \
The calculator supports various operators and functions, including *MIN/MAX*, *negation*, and conditionals *IF*.

## Features
- **Basic Operators**: Supports addition, subtraction, multiplication, and division.
- **Functions**: Includes functionalities for MIN and MAX calculations.
- **Negation**: Allows for negating values easily.
- **Conditional Statements**: Implements simple IF conditions for complex calculations.

## Custom Data Structures
The RPN calculator uses the following custom data structures: \
- **Stack** - holds the numbers and math symbols while the calculator is actively doing the math. \
- **Queue** - helps the program read and understand the math problem you type in line-by-line.

## How to Use
1. Clone the repository: `git clone https://github.com/mateushhh/rpn-calculator`
2. Navigate to the cloned directory: `cd rpn-calculator`
3. Compile the code: `g++ -o rpn_calculator main.cpp`
4. Run the calculator: `./rpn_calculator`
5. Enter RPN expressions as input.

>Make sure you have g++ installed to compile the project
