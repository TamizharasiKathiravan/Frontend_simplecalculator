# 🧮 Simple Frontend Calculator

This is a basic yet fully functional calculator built using **HTML**, **CSS**, and **JavaScript**. It supports simple arithmetic operations like addition, subtraction, multiplication, and division.


## ✨ Features

- Clean and minimal user interface
- Perform basic arithmetic operations: `+`, `−`, `×`, `÷`
- Input numbers using on-screen buttons
- `C` to clear display
- `⌫` to delete last character
- Handles invalid inputs with error display


## 🛠️ Technologies Used

- **HTML** – Structure and layout
- **CSS** – Styling (not included in this upload but referenced)
- **JavaScript** – Logic for all calculator operations


## 📂 Project Structure

simple-calculator/
├── calc.html # Main HTML file with calculator UI
├── style.css # CSS file for design (not included in upload)
├── script.js # JavaScript logic for calculator functions
└── README.md # Project documentation


⚙️ How It Works
User clicks buttons to append values to the input.

calculate() uses JavaScript's eval() to compute the result.

Errors during evaluation are caught and displayed as "Error".

clearDisplay() clears the entire input.

deleteLast() removes the last character from the display.

