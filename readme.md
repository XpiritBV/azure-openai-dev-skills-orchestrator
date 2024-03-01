# Calculator App

This is a simple calculator application that allows users to perform basic mathematical calculations. It also includes a set of unit tests to ensure the accuracy of the calculator's calculations.

## Features

1. Addition: Users can perform addition by entering two numbers and clicking the "+" button.
2. Subtraction: Users can perform subtraction by entering two numbers and clicking the "-" button.
3. Multiplication: Users can perform multiplication by entering two numbers and clicking the "*" button.
4. Division: Users can perform division by entering two numbers and clicking the "/" button.
5. Clear: Users can clear the calculator's display by clicking the "C" button.

## Architecture

This application follows the Domain-Driven Design (DDD) principles to ensure a clear separation of concerns and a maintainable codebase. Below is an overview of the code organization:

- `calculator.py`: This module contains the core logic of the calculator application. It defines the Calculator class, which is responsible for performing the mathematical calculations.
- `main.py`: This module is the entry point of the application. It sets up the user interface and handles user input.
- `tests/`: This directory contains the unit tests for the calculator application. Each test case is defined in a separate file and covers a specific functionality of the calculator.

## Unit Tests

The application includes a set of unit tests to verify the correctness of the calculator's calculations. The tests are organized in the `tests/` directory and follow the naming convention `test_<functionality>.py`. Each test file contains a set of test cases that cover different scenarios.

To run the unit tests, follow these steps:

1. Install the required dependencies by running `pip install -r requirements.txt`.
2. Navigate to the root directory of the project in your terminal.
3. Run the following command: `python -m unittest discover -s tests -p "test_*.py"`.

The test runner will execute all the unit tests and provide a summary of the results.

## Usage

To use the calculator application, follow these steps:

1. Install the required dependencies by running `pip install -r requirements.txt`.
2. Navigate to the root directory of the project in your terminal.
3. Run the following command: `python main.py`.
4. The calculator application will launch, and you can start performing calculations by entering numbers and clicking the corresponding buttons.

## Contributions

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).