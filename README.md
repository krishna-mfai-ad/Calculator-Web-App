# Calculator-Web-App
## Simple Calculator App

This is a simple calculator application built using HTML, CSS, and JavaScript. The calculator has a clean and modern design, with a black and white color scheme and rounded buttons.

### Features

- Basic arithmetic operations: addition, subtraction, multiplication, and division
- Percentage calculation
- Clear and delete functions
- Responsive design that works well on both desktop and mobile devices

### How to Use

1. Open the HTML file in a web browser.
2. Use the on-screen buttons to enter numbers and perform calculations.
3. Click the "AC" button to clear the input field.
4. Click the "DEL" button to delete the last entered character.
5. Click the "=" button to get the result of the calculation.

### Code Structure

The code is divided into two main parts:

1. **HTML Structure**:
   - The main container div with the class "container"
   - The calculator div with the class "calsi"
   - The input field with the id "box"
   - The buttons for the calculator functions, organized into different layers

2. **CSS Styling**:
   - Importing the "Montserrat" font from Google Fonts
   - Styling the body, html, and container elements
   - Defining the styles for the calculator container, including the input field and the button layers
   - Applying specific styles for the different button layers, such as the corner buttons and the zero button

3. **JavaScript Functionality**:
   - Selecting the input field with the id "box"
   - Defining the `display()` function to add the clicked value to the input field
   - Defining the `ac()` function to clear the input field
   - Defining the `equal()` function to evaluate the expression in the input field and display the result
   - Defining the `del()` function to delete the last character from the input field

### Future Improvements

- Add keyboard support for the calculator
- Implement more advanced mathematical functions, such as square root, exponents, and trigonometric functions
- Add a history feature to keep track of previous calculations
- Improve the overall design and user experience
