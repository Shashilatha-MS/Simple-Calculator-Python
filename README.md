# Simple Calculator

A clean, responsive calculator built with HTML, CSS, and vanilla JavaScript. It runs entirely in the browser with no dependencies or build step.

## Features

- Basic arithmetic: addition, subtraction, multiplication, division
- Percentage (`%`) operator
- Decimal number support
- Clear (`C`) to reset the display
- Delete (`DEL`) to remove the last character
- Read-only display showing the current expression

## Project Structure

```
simple-calculator/
├── index.html   # Page layout and calculator buttons
├── style.css    # Styling for the calculator
├── script.js    # Calculator logic
└── README.md    # Project documentation
```

## Getting Started

1. Download or clone the project files into one folder.
2. Open `index.html` in any modern web browser.

No installation or server is required.

## Usage

- Click the number buttons to enter values.
- Click an operator (`÷`, `×`, `−`, `+`, `%`) to build an expression.
- Press `=` to calculate the result.
- Press `DEL` to remove the last entered character, or `C` to clear everything.

## Technologies Used

- **HTML5**: structure and buttons
- **CSS3**: layout and styling
- **JavaScript (ES6)**: calculator functions (`appendValue`, `clearDisplay`, `deleteLast`, `calculate`)

## How It Works

Each button calls a JavaScript function through an `onclick` handler:

| Function | Purpose |
|----------|---------|
| `appendValue(value)` | Adds a digit or operator to the display |
| `clearDisplay()` | Clears the display |
| `deleteLast()` | Removes the last character |
| `calculate()` | Evaluates the expression and shows the result |

## Future Improvements

- Keyboard input support
- Calculation history
- Dark/light theme toggle
- Safer expression parsing in place of `eval()`

## License

This project is open source and free to use for learning and personal projects.
