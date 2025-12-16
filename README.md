# Simple JavaScript Calculator

A clean, minimalist calculator web application built using vanilla web technologies. This project demonstrates DOM manipulation, CSS Grid layouts, and basic event handling.

## Features

* **Basic Arithmetic:** Supports addition, subtraction, multiplication, and division.
* **Dark Theme:** Features a sleek dark gray color scheme with contrasting operator buttons.
* **Responsive Design:** Uses CSS Flexbox to center the application vertically and horizontally on the screen.
* **Interactive UI:** Includes hover and active states for buttons to provide visual feedback to users.
* **Decimal Support:** Allows for precise calculations using decimal points.

## Tech Stack

* **HTML5:** Structures the display screen and button layout.
* **CSS3:** Utilizes **CSS Grid** for the button arrangement and **Flexbox** for the page alignment.
* **JavaScript:** Handles the calculation logic using a simple evaluation function.

## Project Structure

* `index.html`: Contains the main structure, including the display input and the grid of keys.
* `style.css`: Manages the styling, including the rounded buttons (`border-radius: 50px`) and color palette.
* `index.js`: Contains the functional logic:
    * `appendToDisplay(input)`: Adds numbers and operators to the screen.
    * `clearDisplay()`: Resets the calculator.
    * `calculate()`: Evaluates the mathematical expression.

## How to Run

1.  Clone the repository or download the files.
2.  Ensure `index.html`, `style.css`, and `index.js` are in the same directory.
3.  Open `index.html` in any modern web browser.

## Usage

* **Type:** Click numbers to enter them into the display.
* **Calculate:** Press `=` to see the result.
* **Reset:** Press `C` to clear the current entry.
