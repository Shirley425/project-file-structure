# Math Operations Package

A simple Python package that provides basic arithmetic operations.

## Installation

Clone this repository or copy the modules to your project directory.

## Modules and Functions

### `basic_operations.py`
Contains core arithmetic functions:

1. **Addition** (`add(a, b)`)
   - Returns the sum of two numbers
   - Example: `add(5, 3)` returns `8`

2. **Subtraction** (`subtract(a, b)`)
   - Returns the difference between two numbers
   - Example: `subtract(5, 3)` returns `2`

3. **Multiplication** (`multiply(a, b)`)
   - Returns the product of two numbers
   - Example: `multiply(5, 3)` returns `15`

4. **Division** (`divide(a, b)`)
   - Returns the quotient of two numbers
   - Handles division by zero
   - Example: `divide(6, 3)` returns `2.0`

### `advanced_operations.py` (optional)
Contains more complex math functions (can be added later)

## Usage Examples

### Importing specific functions
```python
from basic_operations import add, subtract

result = add(10, 5)  # Returns 15
difference = subtract(10, 5)  # Returns 5
