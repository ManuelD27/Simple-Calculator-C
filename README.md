# Simple Calculator in C

This repository contains a basic calculator program written in C. It performs simple arithmetic operations: addition, subtraction, multiplication, and division.

printf("Enter an operator (+, -, *, /): ");
scanf(" %c", &operator);

switch (operator) {
    case '+':
        result = num1 + num2;
        printf("\nResult: %lf\n", result);
        break;
    case '-':
        result = num1 - num2;
        printf("\nResult: %lf\n", result);
        break;
    // More cases...
}

## How to Use
1. **Clone the repository**:
   ```sh
   git clone https://github.com/ManuelD27/simple-calculator-c.git
   cd simple-calculator-c

