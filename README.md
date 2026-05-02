# 🖤 Hidden-Code-Calculator
A hobby project whose idea came from a youtube short 
A sleek, minimal dark-themed calculator with scientific functions and a hidden secret code feature — built with pure HTML, CSS, and JavaScript.
 
| Preview ১ | Preview ২ |
| :---: | :---: |
| ![Preview 1](Screenshot%202026-05-03%20005956.png) | ![Preview 2](Screenshot%202026-05-03%20010019.png) |
 
---
 
## ✨ Features
 
- **Clean Dark UI** — Full-screen black interface with warm orange accents and smooth ripple effects
- **Standard Calculator** — All basic arithmetic: addition, subtraction, multiplication, division
- **Scientific Mode** — Toggle a scientific panel with trig functions, logarithms, square root, power, constants (π, e), and parentheses
- **Angle Modes** — Switch between DEG, RAD, and GRAD for trigonometric calculations
- **Responsive Layout**
  - Portrait: collapsible scientific panel via SCI toggle
  - Landscape: scientific panel always visible as a top row
- **Keyboard Support** — Full keyboard input for numbers, operators, Enter, Backspace, and Escape
- **Secret Code Easter Egg** — Enter special numeric codes to reveal hidden messages 💕
- **Comfortaa Font** — Rounded, friendly typography via Google Fonts
---
 
## 🚀 Getting Started
 
No installation or build step required.
 
```bash
# Clone the repository
git clone https://github.com/your-username/hdm-calculator.git
 
# Navigate into the folder
cd hdm-calculator
 
# Open in browser
open index.html
````
 
Or simply drag `HDM_calculator.html` into any modern web browser.
 
---
 
## 🎮 Usage
 
### Basic Calculation
 
Tap or click number and operator buttons as you would on any calculator. Press `=` or hit **Enter** to evaluate.
 
### Scientific Functions
 
| Button  | Function                        |
| ------- | ------------------------------- |
| `sin`   | Sine (respects angle mode)      |
| `cos`   | Cosine (respects angle mode)    |
| `tan`   | Tangent (respects angle mode)   |
| `asin`  | Inverse sine                    |
| `acos`  | Inverse cosine                  |
| `atan`  | Inverse tangent                 |
| `log`   | Base-10 logarithm               |
| `ln`    | Natural logarithm               |
| `√`     | Square root                     |
| `xʸ`   | Exponentiation (`**`)           |
| `π`     | Pi constant (`3.14159…`)        |
| `e`     | Euler's number (`2.71828…`)     |
| `( )`   | Parentheses for grouping        |
| `±`     | Toggle positive/negative        |
 
> **Tip:** Unmatched parentheses are auto-closed before evaluation.
 
### Angle Mode
 
Click **DEG**, **RAD**, or **GRAD** at the top to switch the angle unit used in trig functions.
 
### Keyboard Shortcuts
 
| Key            | Action              |
| -------------- | ------------------- |
| `0–9`          | Input digit         |
| `.`            | Decimal point       |
| `+ - * /`      | Operators           |
| `Enter` / `=`  | Calculate           |
| `Backspace`    | Delete last character |
| `Escape`       | Clear all           |
| `( )`          | Parentheses         |
 
---
 
## 🔐 Secret Code Easter Egg
 
Enter a special numeric sequence followed by `%` and press `=` to reveal a hidden message.
 
**Default codes:**
 
| Code   | Message                   |
| ------ | ------------------------- |
| `143%=` | I Love You ❤️             |
| `1437%=`| I Love You Forever 💕     |
 
### Adding Your Own Codes
 
Open the HTML file and find this section near the top of the `<script>` block:
 
```js
const SECRET_CODES = [
  { code: "143",  message: "I Love You ❤️" },
  { code: "1437", message: "I Love You Forever 💕" },
];
```
 
Add, edit, or remove entries as you like. The `code` is the digits before `%`, and `message` is what gets displayed.
 
---
 
## 🗂️ Project Structure
 
```
hdm-calculator/
├── HDM_calculator.html   # Single self-contained file (HTML + CSS + JS)
└── README.md
```
 
---
 
## 🛠️ Tech Stack
 
| Technology     | Purpose                              |
| -------------- | ------------------------------------ |
| HTML5          | Structure                            |
| CSS3           | Styling, animations, responsive layout |
| Vanilla JS     | Calculator logic, secret codes       |
| Google Fonts   | Comfortaa typeface                   |
 
No frameworks. No dependencies. No build tools.
 
---
 
## 🌐 Browser Support
 
Works in all modern browsers:
 
- Chrome / Edge (recommended)
- Firefox
- Safari
- Mobile browsers (iOS Safari, Chrome Android)
---
 
## 📄 License
 
This project is licensed under the [MIT License](LICENSE).
 
---
 
## 🙏 Acknowledgements
 
- Font: [Comfortaa](https://fonts.google.com/specimen/Comfortaa) by Johan Aakerlund via Google Fonts
- Inspired by clean, minimal mobile calculator UIs
---
 
<p align="center">Made with ❤️ by <strong>Zahidul</strong></p>
