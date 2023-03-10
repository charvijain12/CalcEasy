# Simple-Calculator

This program is a simple calculator that allows the user to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. It also has the option to calculate the square of a given number.

The program first prompts the user to choose an option from a menu, and then uses a switch statement to execute the corresponding operation based on the user's choice. It also includes some input validation, such as checking that the user's choice is within the specified range, and checking that the divisor is not zero when performing division.

The program uses the scanf() function to read input from the user, and the printf() function to output the results.

One potential issue with this program is that it assumes that the user will always enter valid input. If the user enters invalid input, such as a non-numeric value, the program may behave unpredictably or crash. To address this, the program could include additional input validation, such as checking that the user has entered a valid numeric value before attempting to use it in a calculation.

Also, in case of choosing option 6 for exit, return 0; statement should be used instead of return;.
