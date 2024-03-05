# Decimal to Binary Converter

This is a simple web application that converts decimal numbers to binary using a recursive algorithm. It includes a visual representation of the recursive process through a call stack animation.

## Features

- Converts decimal numbers to binary.
- Provides a visual representation of the recursive process through a call stack animation.
- Accepts user input via a text input field.
- Supports conversion of decimal numbers up to 5 (for demonstration purposes).

## Technologies Used

- HTML
- CSS
- JavaScript

## How to Use

1. Open the `index.html` file in a web browser.
2. Enter a decimal number in the input field.
3. Click the "Convert" button or press Enter.
4. The binary equivalent of the input decimal number will be displayed in the output field.
5. If the input number is 5, the call stack animation will be triggered, demonstrating the recursive process of converting 5 to binary.

## Directory Structure

- `index.html`: Contains the HTML structure of the web page.
- `styles.css`: Contains the CSS styles for the web page.
- `script.js`: Contains the JavaScript code for the conversion logic and call stack animation.

## Code Structure

- The `decimalToBinary` function in `script.js` implements the recursive algorithm to convert decimal numbers to binary.
- User input validation is performed in the `checkUserInput` function.
- The `showAnimation` function generates the call stack animation based on predefined data in the `animationData` array.
