Real-Time Password Strength Analyzer 
A dynamic web application that evaluates the security level of user-provided passwords. This project focuses on Input Validation and Pattern Recognition, providing instant visual feedback based on security best practices.

Key Features
1.Real-Time Analysis: Evaluates password strength instantly as the user types.
2.Complexity Scoring: Uses logical checks for uppercase letters, lowercase letters, numbers, and special symbols.
3.Visual Strength Meter: A color-coded progress bar that shifts from red (weak) to yellow (medium) to green (strong).


Tech Stack
HTML5: Defines the secure input field and the structural elements for the feedback display.

CSS3: Implements the dynamic styling of the strength meter and the overall UI layout.

JavaScript (ES6+): The core logic engine that utilizes Regular Expressions (Regex) to parse the input and calculate a security score.

This tool implements a Rule-Based Validation System:

Event Capture: The system monitors the input event on the password field.

Constraint Testing: The input string is passed through a series of boolean checks (Regex patterns) to detect specific character sets.

Heuristic Evaluation: The system assigns a weight to each successful check (e.g., length > 8 = +1, special char = +1).

State Transformation: The numeric score is mapped to a CSS class that updates the width and color of the meter in the DOM.
