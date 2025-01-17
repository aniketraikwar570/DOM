# DOM Manipulation Project

## Description
This project demonstrates how to dynamically manipulate the CSS properties of an HTML `div` element using JavaScript's DOM manipulation capabilities. The goal is to change the visual appearance of the element by altering various styles dynamically via JavaScript code.

---

## Features
- Dynamically change the following CSS properties of a `div` element:
  - Background color
  - Margin
  - Padding
  - Font size
  - Font weight
  - Height
  - Width
- Real-time rendering of the changes through JavaScript.
- Minimal and clean layout for better visualization.

---

## Project Files
- **index.html**: Contains the HTML structure of the project.
- **styles.css**: Optional for default styling (basic layout and initial styles).
- **script.js**: JavaScript file to manipulate the styles dynamically.

---

## Setup and Usage Instructions

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd DOM_Manipulation_Project
   ```
3. **Open the HTML File**:
   Open the `index.html` file in any modern web browser to see the changes applied dynamically.

---

## Code Overview

### JavaScript Logic
The project uses JavaScript to achieve DOM manipulation through the following steps:
1. Fetch the `div` element using the `getElementById` method.
2. Apply CSS styles dynamically using the `style` property.

```javascript
const targetDiv = document.getElementById("target-div");

// Apply styles
targetDiv.style.backgroundColor = "yellow";
targetDiv.style.margin = "20px";
targetDiv.style.padding = "10px";
targetDiv.style.fontSize = "18px";
targetDiv.style.fontWeight = "bold";
targetDiv.style.height = "200px";
targetDiv.style.width = "300px";
```

---

## Hosted Link
A live version of the project can be viewed here:
[https://aniketraikwar570.github.io/DOM/](#) *(Update this link after hosting)*

---

## Learning Outcomes
- Fetching HTML elements using JavaScript.
- Dynamically updating CSS styles via the DOM.
- Improving the user interface through JavaScript-based interactions.

---



