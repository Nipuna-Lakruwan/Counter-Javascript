# Counter-Javascript
**Introduction:**
This project is a simple web-based counter application built using HTML, CSS, and JavaScript. It provides basic functionality to increase, decrease, and reset a numerical value displayed on the screen. Let's break down each part of the project:

1. **HTML Structure:**
   - The HTML file defines the structure of the webpage using standard elements like `<html>`, `<head>`, `<body>`, and `<main>`.
   - Inside the `<body>` tag, there's a container `<div>` that holds the counter and buttons for interaction.
   - The counter's initial value is set to 0, and there are three buttons: "decrease," "reset," and "increase."

2. **CSS Styling:**
   - The CSS file (`styles.css`) contains styles for fonts, variables, global styles, and specific styles for the counter section.
   - It imports Google Fonts (`Open Sans` and `Roboto`) for typography and defines a set of custom variables for colors, spacing, shadows, and more.
   - Global styles include settings for the body, headings, paragraphs, and responsive design using media queries.
   - Specific styles for the counter section center the content, style the buttons, and define the appearance of the counter value.

3. **JavaScript Functionality:**
   - The JavaScript file (`app.js`) provides the functionality for the counter.
   - It initializes a variable `count` with an initial value of 0.
   - It selects the counter display element (`<span id="value">`) and the buttons using `querySelector`.
   - Event listeners are added to each button using `forEach` and `addEventListener`.
   - When a button is clicked, the corresponding action (increase, decrease, reset) is performed on the `count` variable, and the updated value is displayed.
   - The color of the counter text changes based on whether the count is positive (green), negative (red), or zero (black).

**Explanation:**
- **HTML:** Defines the structure of the webpage, including the counter display and buttons for interaction.
- **CSS:** Styles the webpage, including fonts, colors, layout, and responsive design.
- **JavaScript:** Adds interactivity to the webpage by handling button clicks, updating the counter value, and changing text color based on the count.

This project demonstrates how HTML, CSS, and JavaScript work together to create a functional and interactive user interface for a simple counter application.
