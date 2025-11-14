Temperature Converter Application

A clean, simple, and responsive web application built with vanilla HTML, CSS, and JavaScript that converts temperatures between Celsius, Fahrenheit, and Kelvin.

This project is an excellent exercise in fundamental front-end web development, focusing on DOM manipulation, user input validation, and event handling.



🚀 Features

Three-Unit Conversion: Convert from:

Celsius (°C) to Fahrenheit (°F) and Kelvin (K)

Fahrenheit (°F) to Celsius (°C) and Kelvin (K)

Kelvin (K) to Celsius (°C) and Fahrenheit (°F)

Live Input Validation:

Prevents conversion if the input field is empty.

Blocks non-numeric inputs (e.g., "abc") and displays a clear error message.

Clean & Responsive UI: A modern, card-based interface that looks great on both desktop and mobile devices.

Dynamic Result Display: The result area updates instantly with the converted values and changes color to highlight the output.

🛠️ Technologies Used

This project is built from scratch using only the core fundamentals of web development.

HTML5: For the semantic structure of the application (form, inputs, labels, buttons).

CSS3 (Internal): For all custom styling, including the maroon/black color theme, responsive layout (using Grid), and focus/hover effects. No external frameworks were used in the final version.

Vanilla JavaScript (ES6+): For all the application logic, including:

DOM manipulation (getElementById, classList.add)

Event handling (addEventListener for the form submission)

Input validation (isNaN, parseFloat)

Conversion formulas

🏃 How to Run This Project

This application is built as a single, standalone file. No server or setup is required.

Clone or download this repository (or just save the .html file).

Double-click the temperature_converter.html file.

It will open directly in your default web browser, and it's ready to use!

💡 What I Learned

DOM Manipulation: Selecting elements and dynamically updating their content (.textContent, .classList) based on user actions.

Form & Event Handling: Using event.preventDefault() on a form submit event to control the page and prevent it from refreshing.

Input Validation: The importance of sanitizing user input (trim(), isNaN()) to prevent errors and provide a better user experience.

Pure CSS Styling: Building a responsive and modern-looking component from scratch without relying on a large framework like Tailwind or Bootstrap.
