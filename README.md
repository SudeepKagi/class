# 🚀 class - A Simple Web-Based Calculator
<div align="center">

![Badge](https://img.shields.io/badge/class-A_Simple_Web_Based_Calculator-4F46E5?style=for-the-badge)
[![GitHub stars](https://img.shields.io/github/stars/SudeepKagi/class?style=for-the-badge)](https://github.com/SudeepKagi/class/stargazers)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

**Perform Basic Arithmetic Operations with Ease**

[Addition](#features) • [Subtraction](#features) • [Multiplication](#features) • [Division](#features) • [Installation](#installation) • [Usage](#usage)
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
  + Addition: allows users to add two numbers together
  + Subtraction: allows users to subtract one number from another
  + Multiplication: allows users to multiply two numbers together
  + Division: allows users to divide one number by another
* **User Interface**:
  + Simple and intuitive design
  + Easy to use input fields for entering numbers
  + Clear and concise display of calculation results
* **Error Handling**:
  + Handles division by zero errors
  + Handles invalid input errors

---

## 🏗️ Architecture
```
┌────────────┐
│  index.html  │
├────────────┤
│  app.js     │
├────────────┤
│  Calculator  │
│  (HTML, JS)  │
├────────────┤
│  User Input  │
│  (Numbers)    │
├────────────┤
│  Calculation  │
│  (Add, Sub,   │
│   Mul, Div)   │
├────────────┤
│  Result Display│
└────────────┘
```

---

## 🛠️ Tech Stack
| Technology | Purpose | Version |
| --- | --- | --- |
| HTML5 | User Interface | 5 |
| JavaScript | Calculator Logic | ES6 |
| CSS | Styling | 3 |

Note: The versions listed are based on the code provided and may not reflect the latest versions available.

---

## 📦 Installation
### Prerequisites
* A web browser (e.g. Google Chrome, Mozilla Firefox)
* A code editor (e.g. Visual Studio Code, Sublime Text)

### Steps
1. Clone the repository using the following command:
```bash
git clone https://github.com/SudeepKagi/class.git
```
2. Open the `index.html` file in a web browser to use the calculator.
3. To edit the code, open the `app.js` file in a code editor and make changes as needed.

---

## 🚀 Usage
To use the calculator, simply open the `index.html` file in a web browser and enter two numbers in the input fields. Then, select the desired arithmetic operation using the buttons provided. The result will be displayed below the input fields.

Example:
```javascript
// Add two numbers together
function add() {
  let a = Number(document.getElementById("num1").value);
  let b = Number(document.getElementById("num2").value);
  document.getElementById("result").innerText = "Result: " + (a + b);
}
```
To perform a calculation, call the corresponding function (e.g. `add()`, `sub()`, etc.) and pass in the desired numbers.

---

## 📡 API Documentation
Since this is a simple web-based calculator, there is no API to document. However, the calculator does provide a simple interface for performing arithmetic operations.

---

## 🤝 Contributing
To contribute to this project, please follow these steps:

1. Fork the repository using the "Fork" button on GitHub.
2. Clone the forked repository to your local machine using the following command:
```bash
git clone https://github.com/your-username/class.git
```
3. Make changes to the code as needed.
4. Commit the changes using the following command:
```bash
git commit -m "Your commit message"
```
5. Push the changes to your forked repository using the following command:
```bash
git push origin your-branch-name
```
6. Create a pull request to merge the changes into the main repository.

---

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 📈 Project Stats
![GitHub stars](https://img.shields.io/github/stars/SudeepKagi/class?style=social) ![GitHub forks](https://img.shields.io/github/forks/SudeepKagi/class?style=social) ![GitHub issues](https://img.shields.io/github/issues/SudeepKagi/class) ![GitHub last commit](https://img.shields.io/github/last-commit/SudeepKagi/class)

---

<div align="center">
### ⭐ Star this repository if you find it helpful!
**Built with ❤️ by SudeepKagi**
[GitHub](https://github.com/SudeepKagi)
</div>