# Calculator Project

A simple console-based calculator application written in Python.

## Description

This project provides a basic calculator that can perform four fundamental arithmetic operations:
- Addition
- Subtraction
- Multiplication
- Division

The calculator runs in the console/terminal and provides a user-friendly menu interface for selecting operations.

## Features

- **Addition**: Add two numbers
- **Subtraction**: Subtract one number from another
- **Multiplication**: Multiply two numbers
- **Division**: Divide one number by another (includes error handling for division by zero)
- **Input Validation**: Handles invalid numeric inputs gracefully
- **Interactive Menu**: Easy-to-use menu system
- **Exit Option**: Clean exit from the application

## Requirements

- Python 3.x

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/rahit91890/calculator-project.git
   ```

2. Navigate to the project directory:
   ```bash
   cd calculator-project
   ```

## Usage

Run the calculator using Python:

```bash
python calculator.py
```

Follow the on-screen prompts:
1. Select an operation (1-5)
2. Enter the first number
3. Enter the second number
4. View the result
5. Repeat or exit (option 5)

## Example

```
=== Simple Calculator ===
Select operation:
1. Add
2. Subtract
3. Multiply
4. Divide
5. Exit

Enter choice (1/2/3/4/5): 1
Enter first number: 10
Enter second number: 5

Result: 10.0 + 5.0 = 15.0
```

## Error Handling

- **Division by Zero**: Returns an error message instead of crashing
- **Invalid Input**: Catches non-numeric inputs and prompts the user to enter valid values
- **Invalid Menu Choice**: Prompts user to select a valid operation

## Author

Created by **Codaphics Official**

## License

This project is open source and available for educational purposes.

## Contributing

Feel free to fork this repository and submit pull requests for any improvements.

## Future Enhancements

- Add more advanced operations (square root, power, modulo)
- Implement calculation history
- Add support for multiple operations in sequence
- Create a GUI version

---

*Happy Calculating! 🧮*
