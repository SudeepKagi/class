# 🚀 class - A Simple Web-Based Calculator
<div align="center">

![Badge](https://img.shields.io/badge/class-A_Simple_Web_Based_Calculator-4F46E5?style=for-the-badge)
[![GitHub stars](https://img.shields.io/github/stars/SudeepKagi/class?style=for-the-badge)](https://github.com/SudeepKagi/class/stargazers)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

**Perform Basic Arithmetic Operations with Ease**

[Addition](#features) • [Subtraction](#features) • [Multiplication](#features) • [Division](#installation) • [Usage](#usage)
</div>

---

## 🎯 Overview
The class repository is a simple web-based calculator that allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. This project exists to provide a straightforward and intuitive way for users to perform calculations without the need for external libraries or frameworks. The calculator is built using HTML5, JavaScript, and is designed to be easy to use and understand, making it accessible to a wide range of users.

### Why class?
- **💻 Easy to Use**: The calculator has a simple and intuitive interface that makes it easy for users to perform calculations.
- **📊 Fast Calculations**: The calculator performs calculations in real-time, providing users with instant results.
- **🔒 No External Dependencies**: The calculator does not rely on any external libraries or frameworks, making it lightweight and easy to maintain.
- **📈 Cross-Browser Compatibility**: The calculator is designed to work on multiple browsers, ensuring that users can access it from their preferred browser.

---

## ✨ Features
* **Arithmetic Operations**:
  + Addition: performs addition of two numbers
  + Subtraction: performs subtraction of two numbers
  + Multiplication: performs multiplication of two numbers
  + Division: performs division of two numbers
* **User Interface**:
  + Simple and intuitive interface
  + Input fields for two numbers
  + Buttons for each operation
  + Display field for results
* **Error Handling**:
  + Handles invalid input (e.g., non-numeric characters)
  + Handles division by zero errors

---

## 🏗️ Architecture
```
┌────────────────────┐
│  index.html     │
│  (User Interface) │
└────────────────────┘
           ↓
┌────────────────────┐
│  app.js          │
│  (Calculator Logic) │
└────────────────────┘
```

---

## 🛠️ Tech Stack
| Technology | Purpose | Version |
| --- | --- | --- |
| HTML5 | Structuring and presenting content | 5 |
| JavaScript | Handling user input and performing calculations | ES6 |
| No external libraries or frameworks are used |  |  |

---

## 📦 Installation
### Prerequisites
* A web browser (e.g., Google Chrome, Mozilla Firefox)
* A code editor (e.g., Visual Studio Code, Sublime Text)

### Steps
1. Clone the repository using `git clone https://github.com/SudeepKagi/class.git`
2. Navigate to the `calculator` directory
3. Open the `index.html` file in a web browser

```bash
git clone https://github.com/SudeepKagi/class.git
cd calculator
```

```javascript
// Open index.html in a web browser
```

---

## 🚀 Usage
To use the calculator, simply open the `index.html` file in a web browser and follow these steps:

```javascript
// Enter two numbers
document.getElementById("num1").value = 10;
document.getElementById("num2").value = 5;

// Perform addition
add();

// Perform subtraction
sub();

// Perform multiplication
mul();

// Perform division
div();
```

```html
<!-- Example usage -->
<input type="number" id="num1" value="10">
<input type="number" id="num2" value="5">
<button onclick="add()">+</button>
<button onclick="sub()">-</button>
<button onclick="mul()">×</button>
<button onclick="div()">÷</button>
<h3 id="result">Result: </h3>
```

---

## 📡 API Documentation
No API is exposed by this application, as it is a simple web-based calculator.

---

## 🤝 Contributing
Contributions are welcome! To contribute to the class repository, follow these steps:

1. Fork the repository using the "Fork" button on GitHub
2. Make changes to the code and commit them with a descriptive message
3. Create a pull request to merge your changes into the main repository
4. Ensure that your changes do not break existing functionality

```bash
git fork https://github.com/SudeepKagi/class.git
git clone https://github.com/your-username/class.git
cd class
git add .
git commit -m "Descriptive commit message"
git push origin your-branch
```

---

## 📜 License
The class repository is licensed under the MIT License. See the LICENSE file for more information.

---

## 📈 Project Stats
![GitHub stars](https://img.shields.io/github/stars/SudeepKagi/class?style=social) ![GitHub forks](https://img.shields.io/github/forks/SudeepKagi/class?style=social) ![GitHub issues](https://img.shields.io/github/issues/SudeepKagi/class) ![GitHub last commit](https://img.shields.io/github/last-commit/SudeepKagi/class)

---

<div align="center">
### ⭐ Star this repository if you find it helpful!
**Built with ❤️ by SudeepKagi**
[GitHub](https://github.com/SudeepKagi)
</div>