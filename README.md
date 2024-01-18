# Mathematical Operations Menu

This Python script implements a menu-driven program with the following mathematical operations:

1. **Draw Rectangle**: Takes user input for vertical and horizontal side lengths and prints a rectangle of '*' characters.

2. **Calculate Info of Rectangle**: Takes user input for side lengths of a rectangle, calculates its area and perimeter, and determines if it's a square.

3. **Calculate Factorial**: Takes user input for a number and calculates its factorial.

4. **Calculate Combination [C(n, k)]**: Takes user input for n and k, calculates the combination (n choose k).

0. **Exit**: Allows the user to exit the program.

## Functions

- **getNumber(lowerLimit, upperLimit)**: Ensures user input is within specified limits.

- **drawRectangle(verticalSide, horizontalSide)**: Prints a rectangle of '*' characters.

- **calculateRectangleInfo(side1, side2)**: Calculates the area, perimeter, and checks if a rectangle is a square.

- **factorial(number)**: Calculates the factorial of a number.

- **combination(n, k)**: Calculates the combination (n choose k).

- **showMenu()**: Prints the menu options.

- **main()**: The main function that controls the flow of the program.

## Execution

The program repeatedly shows the menu until the user chooses to exit. For each operation, it takes user input, performs the calculation, and displays the result.

## User Input Validation

The script uses the `getNumber()` function to validate user input, ensuring that it falls within the specified limits.

## Exit Confirmation

When the user chooses to exit, the script asks for confirmation, and it will keep asking until a valid response is given.

## Note

- The script includes a prompt for the horizontal side length of the rectangle in the "Draw Rectangle" option, but the variable `horizontalSide` is not used in the `drawRectangle` function. If it's intended to be used, you may want to modify the function accordingly.

- If the user inputs '0' for the vertical side length in the "Draw Rectangle" option, the script may not behave as expected. You may want to handle this case if necessary.

Feel free to make any modifications or improvements based on your requirements.
