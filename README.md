# Java Calculator Application

This is a simple command-line calculator built in Java. It provides the following features:

- Addition
- Subtraction
- Multiplication
- Division
- Square
- Cube
- Square Root

It also includes:
- Exception handling for invalid inputs (e.g., non-numeric entries).
- Arithmetic error management like division by zero and square root of negative numbers.

## How to Use

1. **Compile the code:**

   Make sure both `Main.java` and `Calculator.java` are in the same directory. Then run:
   ```bash
   javac Main.java
   ```

2. **Run the application:**
   ```bash
   java Main
   ```

3. **Follow the menu prompts** to select an operation (1-8) and enter the required numbers.

---

## Project Structure

- `Main.java`  
  Contains the main logic to interact with users via the console. It displays a menu, handles user input, and calls the relevant methods in the `Calculator` class.

- `Calculator.java`  
  A utility class with static methods for each mathematical operation (addition, subtraction, etc.). It includes basic validation and throws appropriate exceptions for illegal operations.

---

## Exception Handling

The application includes:

- **InputMismatchException**: Catches non-numeric input from the user.
- **ArithmeticException**: Handles division by zero.
- **IllegalArgumentException**: Handles invalid arguments such as square root of negative numbers.
- **General Exception**: Catches any unexpected runtime issues.

---
## Author

Utkarsh Lakhani
