# Basic Calculator

This is a simple, responsive calculator built with **HTML**, **CSS**, and **JavaScript**. It performs basic arithmetic operations such as addition, subtraction, multiplication, and division, and displays both the input numbers and operators dynamically.

## Features
- Basic arithmetic operations: **Addition (+)**, **Subtraction (-)**, **Multiplication (×)**, **Division (÷)**.
- Clear button to reset the display and calculations.
- Real-time display of input numbers and selected operators.
- Responsive layout using CSS Grid.
## Live Demo
You can use this calculator by opening the index`.html` file in any modern web browser.

## File Structure
All the code (HTML, CSS, and JavaScript) is contained in a single index`.html` file.

### HTML Structure
- A container (`div.calculator` ) for the calculator.
- A display (`div.display` ) to show the input and results.
- Buttons (`button.btn` ) for digits (0-9), operators, and functions like clearing the input or calculating the result.
### CSS Styling
- A responsive layout using **CSS Grid** to position the calculator buttons.
- Simple and clean styling, with hover effects for better user interaction.
- Separate styles for the operator buttons and the clear button for clarity.
### JavaScript Logic
- **Event Listeners** are added to all buttons to capture user input.
- Handles the operations:
    - Displays numbers as they are clicked.
    - Displays operators on the screen when clicked.
    - Computes and displays results when the equal (`=` ) button is clicked.
    - Clears the display when the clear (`C` ) button is clicked.
- The `eval()`  function is used for quick arithmetic calculations between the stored values and operator.
## Code Snippets
### Displaying Operator on Screen
When an operator button is clicked, it is displayed on the screen along with the numbers:

```
```
// Handle operators 
if (['+', '-', '*', '/'].includes(value)) {
   if (currentInput) { 
  previousInput = currentInput; currentInput = ''; 
  operator = value; 
  display.innerText += ` ${e.target.textContent} `;
   } 
   return; 
   } 
```

```
## How to Use
1. Clone or download the repository.
2. Open the index`.html`  file in any web browser.
3. Start performing calculations by clicking the buttons.
## Technologies Used
- **HTML**: For the structure of the calculator.
- **CSS**: For styling and layout using the CSS Grid system.
- **JavaScript**: For adding interactivity and performing calculations.
## Future Improvements
- Add keyboard support for better accessibility.
- Implement error handling for cases like dividing by zero.
- Improve design for better responsiveness on mobile devices.


