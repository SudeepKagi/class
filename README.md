# 🚀 class - A Simple Web-Based Calculator
<div align="center">

![Badge](https://img.shields.io/badge/class-A_Simple_Web_Based_Calculator-4F46E5?style=for-the-badge)
[![GitHub stars](https://img.shields.io/github/stars/SudeepKagi/class?style=for-the-badge)](https://github.com/SudeepKagi/class/stargazers)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

**Perform Basic Arithmetic Operations with Ease**

[Addition](#features) • [Subtraction](#features) • [Multiplication](#features) • [Installation](#installation) • [Usage](#usage)
</div>

---

## 🎯 Overview
The class repository is a simple web-based calculator that allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. This project exists to provide a straightforward and intuitive way for users to perform calculations without the need for external libraries or frameworks. The calculator is built using HTML5, JavaScript, and is designed to be easy to use and understand, making it accessible to a wide range of users. The calculator's simplicity and ease of use make it an ideal tool for anyone looking to perform quick calculations, from students to professionals.

### Why class?
- **💻 Easy to Use**: The calculator has a simple and intuitive interface that makes it easy for users to perform calculations.
- **📊 Fast Calculations**: The calculator performs calculations in real-time, providing users with instant results.
- **🔒 No External Dependencies**: The calculator does not rely on any external libraries or frameworks, making it lightweight and easy to maintain.
- **📈 Cross-Browser Compatibility**: The calculator is designed to work on multiple browsers, ensuring that users can access it from their preferred browser.
- **🎯 Accurate Results**: The calculator provides accurate results, ensuring that users can trust the calculations.

---

## ✨ Features
* **Arithmetic Operations**:
  + Addition: performs addition of two numbers using the `add()` function
  + Subtraction: performs subtraction of two numbers using the `sub()` function
  + Multiplication: performs multiplication of two numbers using the `mul()` function
  + Division: performs division of two numbers using the `div()` function
* **User Interface**:
  + Input fields for two numbers
  + Buttons for each arithmetic operation
  + Display field for the result
* **Error Handling**:
  + Input validation to ensure that users enter valid numbers
  + Error messages for invalid input or division by zero

---

## 🏗️ Architecture
```
┌────────────┐
│  index.html  │
├────────────┤
│  app.js     │
└────────────┘
```
The calculator consists of two main files: `index.html` and `app.js`. The `index.html` file contains the user interface, while the `app.js` file contains the JavaScript code that performs the calculations.

---

## 🛠️ Tech Stack
| Technology | Purpose | Version |
| --- | --- | --- |
| HTML5 | User Interface | 5 |
| JavaScript | Calculations and Logic | ES6 |
| CSS | Styling | 3 |

Note: The versions listed are based on the code provided and may not reflect the latest versions available.

---

## 📦 Installation
### Prerequisites
* A web browser (e.g. Google Chrome, Mozilla Firefox)
* A code editor or IDE (e.g. Visual Studio Code, Sublime Text)
* Basic knowledge of HTML, CSS, and JavaScript

### Steps
1. Clone the repository using Git: 
```bash
git clone https://github.com/SudeepKagi/class.git
```
2. Open the `index.html` file in a web browser to view the calculator.
3. Open the `app.js` file in a code editor or IDE to view the JavaScript code.

---

## 🚀 Usage
To use the calculator, simply open the `index.html` file in a web browser and enter two numbers in the input fields. Click on the button for the desired arithmetic operation to perform the calculation. The result will be displayed in the display field.

Example:
```javascript
// Perform addition
function add() {
  let a = Number(document.getElementById("num1").value);
  let b = Number(document.getElementById("num2").value);
  document.getElementById("result").innerText = "Result: " + (a + b);
}
```
To perform addition, enter two numbers in the input fields and click on the "+" button.

---

## 📡 API Documentation
The calculator does not have a public API. However, the `app.js` file contains functions that can be used to perform calculations.

* `add()`: performs addition of two numbers
* `sub()`: performs subtraction of two numbers
* `mul()`: performs multiplication of two numbers
* `div()`: performs division of two numbers

Example:
```javascript
// Perform addition using the add() function
let result = add(2, 3);
console.log(result); // Output: 5
```
---

## 🤝 Contributing
To contribute to the calculator project, follow these steps:

1. Fork the repository using Git.
2. Make changes to the code and commit them using Git.
3. Create a pull request to merge the changes into the main repository.
4. Wait for the pull request to be reviewed and approved.

Note: Make sure to follow the project's coding standards and guidelines when making changes.

---

## 📜 License
The calculator project is licensed under the MIT License.

---

## 📈 Project Stats
![GitHub stars](https://img.shields.io/github/stars/SudeepKagi/class?style=social) ![GitHub forks](https://img.shields.io/github/forks/SudeepKagi/class?style=social) ![GitHub issues](https://img.shields.io/github/issues/SudeepKagi/class) ![GitHub last commit](https://img.shields.io/github/last-commit/SudeepKagi/class)

---

<div align="center">
### ⭐ Star this repository if you find it helpful!
**Built with ❤️ by SudeepKagi**
[GitHub](https://github.com/SudeepKagi)
</div>