# Natural Number Calculator

This project is a simple Reverse Polish Notation (RPN) calculator that performs exact arithmetic operations on natural numbers with no explicit bounds on their values. This calculator is unlike any other calculator you have likely seen before.

## Table of Contents

1. [Problem](#problem)
2. [Method](#method)
3. [Code Structure](#code-structure)
4. [Running the Program](#running-the-program)
5. [Contributing](#contributing)
6. [License](#license)

## Problem

The calculator performs basic arithmetic operations on natural numbers. It handles two operands, both of which always have natural number values. Direct entry of a number is always to the bottom operand in the display. The "Clear" button sets the bottom operand to 0. The "Swap" button exchanges the values of the two operands. The "Enter" button copies the value of the bottom operand to the top operand.

Each operator button operates on the two operands in their natural order as displayed in the interface (e.g., "-" subtracts the bottom operand from the top operand), and each replaces the bottom operand with the result of the operator and the top operand with 0; except that division replaces the bottom operand with the quotient and the top operand with the remainder.

## Method

The project involves filling in the bodies of several methods in the model (NNCalcModel1), view (NNCalcView1), and controller (NNCalcController1) classes. Unit-testing the code with JUnit is recommended.

## Code Structure

The code is structured as follows:

- `NaturalNumberCalculator.java`: This is the main program that sets up the main application window and starts user interaction.
- `NNCalcController1.java`: This is the controller class that handles user interactions and updates the model and view accordingly.
- `NNCalcModel1.java`: This is the model class that holds the data and the operations that can be performed on the data.
- `NNCalcView1.java`: This is the view class that handles the GUI of the calculator.

## Running the Program

To run the program, execute the main program in `NaturalNumberCalculator.java`. Do some "system testing" of your full calculator until you are satisfied it works.

## Authors

Adewale Adenle, Bruce W. Weide

## Acknowledgments

The components used in this project are from the Ohio State University Standard Library.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
