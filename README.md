# Build-a-Simple-Calculator


# Simple Command-Line Calculator

A basic command-line calculator that performs arithmetic operations (addition, subtraction, multiplication, division) with robust error handling.

## Features
- Performs basic arithmetic operations: addition, subtraction, multiplication, division
- Continuous operation until user chooses to exit
- Graceful handling of invalid inputs:
  - Non-numeric inputs
  - Division by zero
  - Invalid operation commands
- User-friendly interface with clear prompts and error messages

## Requirements
- Python 3.x (tested on Python 3.6+)
- No external dependencies required

## Installation & Running
1. Save the code to a file named `calculator.py`
2. Open a terminal/command prompt
3. Navigate to the directory containing the file
4. Run the script:
   ```bash
   python calculator.py
   ```

## Usage Instructions
1. When prompted, enter one of the following operations:
   - `add` for addition
   - `sub` for subtraction
   - `mul` for multiplication
   - `div` for division
2. Enter two numbers when prompted
3. View the result
4. Continue performing operations or type `exit` to quit

## Example Usage
```
Simple Command-Line Calculator
Operations: add, sub, mul, div
Enter 'exit' to quit

Enter operation (add, sub, mul, div) or 'exit' to quit: add
Enter first number: 5
Enter second number: 3
Result: 8.0

Enter operation (add, sub, mul, div) or 'exit' to quit: div
Enter first number: 10
Enter second number: 2
Result: 5.0

Enter operation (add, sub, mul, div) or 'exit' to quit: exit
Exiting calculator. Goodbye!
```

## Error Handling Examples
1. **Invalid Operation**:
   ```
   Enter operation (add, sub, mul, div) or 'exit' to quit: power
   Invalid operation. Please choose from add, sub, mul, div.
   ```

2. **Non-Numeric Input**:
   ```
   Enter operation (add, sub, mul, div) or 'exit' to quit: add
   Enter first number: five
   Invalid input. Please enter numeric values.
   ```

3. **Division by Zero**:
   ```
   Enter operation (add, sub, mul, div) or 'exit' to quit: div
   Enter first number: 5
   Enter second number: 0
   Error: Division by zero is not allowed.
   ```

## Future Enhancements
- Support for more operations (exponents, modulo, square root)
- History of calculations
- Scientific calculator functions
- Parentheses for order of operations
- Support for different number formats (fractions, scientific notation)

