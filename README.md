# Scientific-Calculator-Web-App-
This project is a responsive Scientific Calculator built using HTML, Tailwind CSS, and vanilla JavaScript. It combines a clean, modern UI with powerful calculation features, making it suitable for both basic and advanced math operations.

Features
Basic operations: Addition, subtraction, multiplication, division, decimal input.

Scientific functions:

Square root (√)
Square (x²)
Sine, Cosine, Tangent
Logarithm (log base 10) and Natural log (ln)
Constants: π (Pi), e (Euler’s Number)

Other functions:
Brackets support ( )
Delete last entry button (DEL)
Clear entire input (C)
Error handling for invalid inputs

Responsive UI:
Built with Tailwind CSS for a modern design
Works well on both desktop and mobile devices
Google Fonts (Inter) for a clean look
Custom button animations and styled scrollbar

Technologies Used
HTML5: Structural layout of the calculator
Tailwind CSS: Styling for responsiveness and modern UI
JavaScript (ES6): Core calculator logic and scientific functions

How It Works
The calculator has an input display where expressions are shown.
Buttons allow users to insert numbers, operators, or scientific functions.
Pressing = evaluates the expression using JavaScript’s eval() function (with symbol replacements like ÷ → / and × → *).
Scientific operations like sin, cos, sqrt, etc., are wrapped in JavaScript’s Math functions.
Results are rounded to 10 decimal places to avoid floating-point inconsistencies.

Project Preview
Dark theme with rounded buttons.
Smooth hover and active effects.
Scientific mode accessible in the first two rows of buttons.

Future Improvements
Add memory functions (M+, M-, MR).
Support degrees/radians toggle for trigonometric operations.
Improve parser to avoid reliance on eval() for security.
