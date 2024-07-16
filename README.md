Head Section:
Document Type and Language:

Declares <!DOCTYPE html> for HTML5 and specifies lang="en" for English language.
Styles:

Defines CSS rules to reset default styles (padding: 0; margin: 0;) and set the font family to 'Poppins'.
Styles the body to have a background color (#495250), display as a grid (display: grid), and center its contents (place-items: center).
Body Section:
Calculator Layout (div.main):

Contains the calculator interface within a 400px wide and 450px high container with a white background, a black border (5px solid), and rounded corners (border-radius: 6px).
The calculator display (input[type='text']) occupies most of the space, aligned to the right, styled to resemble a typical calculator input field.
Button Layout (div.btn):

Contains the calculator buttons, styled as input elements (input[type='button']).
Each button corresponds to a digit, arithmetic operation, or control function (C, %, ←, /, 7, 8, 9, x, 4, 5, 6, -, 1, 2, 3, +, 00, 0, ., =).
Buttons are styled with padding, margins, background color (#495250), and transitions for hover effects (transition: 0.5s).
JavaScript Functionality (script):
Function Solve(val):

Appends the clicked button value (val) to the calculator display (input[type='text']).
Function Result():

Evaluates the expression entered in the calculator display using JavaScript's eval() function.
Displays the result in the calculator display.
Function Clear():

Clears the content of the calculator display.
Function Back():

Removes the last character from the calculator display, simulating a backspace functionality.# Calculator-
