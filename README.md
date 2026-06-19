<img width="1907" height="917" alt="Calculator" src="https://github.com/user-attachments/assets/a7cc589a-fd1d-4d7e-88c3-b366db21ce17" />

# Calculator Web Application

## 📌 Overview

This project is a simple and responsive Calculator built using HTML, CSS, and JavaScript. It performs basic arithmetic operations such as addition, subtraction, multiplication, and division through an interactive user interface.

The calculator uses JavaScript to process user input, display expressions, and calculate results dynamically.

---

## 🚀 Features

* Basic arithmetic operations

  * Addition (+)
  * Subtraction (-)
  * Multiplication (*)
  * Division (/)
* Clear display functionality
* Delete last entered character
* Error handling for invalid expressions
* User-friendly interface
* Real-time display updates

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)

---

## 📂 Project Structure

```text
calculator/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## 💻 JavaScript Logic

### Append Input

```javascript
function appendToDisplay(input){
    display.value += input;
}
```

Adds numbers and operators to the calculator display.

---

### Clear Display

```javascript
function ClearDisplay(){
    display.value = "";
}
```

Clears the entire display.

---

### Calculate Result

```javascript
function Calculate(){
    try {
        display.value = eval(display.value);
    } catch (error) {
        display.value = "Error";
    }
}
```

Evaluates the mathematical expression and displays the result.

---

### Delete Last Character

```javascript
function deleteLast() {
    display.value = display.value.slice(0, -1);
}
```

Removes the last entered character from the display.

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/calculator-web-app.git
cd calculator-web-app
```

### Open the Application

Simply open:

```text
index.html
```

in your browser.

No additional installation is required.

---

## 📋 Sample Operations

| Expression | Result |
| ---------- | ------ |
| 10 + 5     | 15     |
| 20 - 8     | 12     |
| 6 * 7      | 42     |
| 100 / 4    | 25     |

---

## 🧠 Concepts Covered

* DOM Manipulation
* Event Handling
* Functions
* String Operations
* Error Handling using try-catch
* JavaScript Expressions
* Front-End Web Development

---

## ⚠️ Note

This project uses:

```javascript
eval()
```

for expression evaluation.

While suitable for learning purposes, `eval()` is generally not recommended for production applications due to security and performance concerns.

---

## 🔮 Future Improvements

* Scientific Calculator Functions
* Keyboard Support
* Dark/Light Theme Toggle
* Calculation History
* Percentage Operations
* Square Root and Power Functions
* Responsive Mobile Design
* Replace `eval()` with a safer expression parser

---

## 🎯 Learning Outcomes

Through this project, you will learn:

* JavaScript DOM Manipulation
* User Interface Interaction
* Event-Driven Programming
* Error Handling
* Building Interactive Web Applications

---

## 👨‍💻 Author

Pranay Jadhao

Electronics & Telecommunication Engineer

Aspiring Software Engineer | Python | JavaScript | SQL

LinkedIn: [www.linkedin.com/in/pranayjadhao](http://www.linkedin.com/in/pranayjadhao)

GitHub: https://github.com/

---

## 📄 License

This project is open-source and available for educational and learning purposes.
