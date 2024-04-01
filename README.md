# Simple Stopwatch

This is a simple stopwatch project created using HTML, CSS, and JavaScript with DOM manipulation.

## Project Overview

This project aims to demonstrate how to create a stopwatch using DOM manipulation in JavaScript. The stopwatch allows users to start, stop, and reset the timer.

## Technologies Used

- HTML
- CSS
- JavaScript

## How to Use

1. Clone this repository to your local machine.
2. Open the `index.html` file in your web browser.
3. Click the "Start" button to begin the stopwatch.
4. Click the "Stop" button to pause the stopwatch.
5. Click the "Reset" button to reset the stopwatch to zero.

## Understanding the Code

### HTML

The HTML file (`index.html`) contains the structure of the stopwatch interface. It includes buttons for starting, stopping, and resetting the stopwatch, as well as a display area to show the elapsed time.

### JavaScript

The JavaScript file (`script.js`) contains the functionality for the stopwatch. It uses DOM manipulation to interact with the HTML elements, such as updating the display and handling button click events.

In the JavaScript code:

- **Selecting Elements**: The `document.querySelector()` method is used to select HTML elements by their CSS selectors. These elements represent the start/stop button, reset button, and timer display area, respectively.

- **Event Handling**: Event listeners are added to the start/stop and reset buttons using `addEventListener()` to detect when they are clicked. When the start/stop button is clicked, it either starts or stops the stopwatch based on its current state. Similarly, when the reset button is clicked, it resets the stopwatch to zero.

- **Updating the Display**: Inside the `stopWatch()` function, the `innerText` property of the timer display element is updated to show the elapsed time. This is done by concatenating the hours, minutes, and seconds with leading zeros to ensure a consistent format (`HH:MM:SS`).

## Contributions

Contributions to this project are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

