# 🧮 Basic Calculator

A simple **Basic Calculator** made using **HTML and JavaScript**.

This project takes two numbers from the user and performs four basic mathematical operations:

* ➕ Addition
* ➖ Subtraction
* ✖️ Multiplication
* ➗ Division

---

## 📸 Project Preview

The calculator has two input boxes and four buttons for performing calculations.

<img width="1686" height="874" alt="Screenshot 2026-08-13 175047" src="https://github.com/user-attachments/assets/6fe346ad-9b27-4dee-a1ae-2ea27addcbf9" />


### Example

If the user enters:

```text
First Number: 2
Second Number: 8
```

Clicking **ADD** gives:

```text
Result: 10
```

---

## 🛠️ Technologies Used

* **HTML** — Creates the calculator interface.
* **JavaScript** — Performs the calculations and displays the result.

---

## 📁 Project Structure

```text
Open-Source/
│
├── Basic calculator.txt
└── README.md
```

The `Basic calculator.txt` file contains the HTML and JavaScript code.

---

## ⚙️ How the Calculator Works

### 1. Enter Two Numbers

The calculator has two input fields:

```html
<input type="number" id="num1">
<input type="number" id="num2">
```

These are used to take the first and second numbers from the user.

### 2. Choose an Operation

There are four buttons:

```html
<button onclick="add()">ADD</button>
<button onclick="subtract()">SUBTRACT</button>
<button onclick="multiply()">MULTIPLY</button>
<button onclick="divide()">DIVIDE</button>
```

Each button calls a different JavaScript function.

### 3. Get the Numbers

JavaScript gets the values entered by the user:

```javascript
const a = Number(document.getElementById("num1").value);
const b = Number(document.getElementById("num2").value);
```

`Number()` converts the input into a number so that mathematical calculations can be performed.

### 4. Display the Result

The result is displayed using:

```javascript
document.getElementById("result").innerHTML = "Result:" + (a + b);
```

---

## ➕ Addition

The `add()` function adds the two numbers:

```javascript
function add() {
    const a = Number(document.getElementById("num1").value);
    const b = Number(document.getElementById("num2").value);

    document.getElementById("result").innerHTML =
        "Result:" + (a + b);
}
```

Example:

```text
2 + 8 = 10
```

---

## ➖ Subtraction

The `subtract()` function subtracts the second number from the first:

```javascript
a - b
```

Example:

```text
8 - 2 = 6
```

---

## ✖️ Multiplication

The `multiply()` function multiplies the two numbers:

```javascript
a * b
```

Example:

```text
2 × 8 = 16
```

---

## ➗ Division

The `divide()` function divides the first number by the second:

```javascript
a / b
```

Example:

```text
8 ÷ 2 = 4
```

---

## 🚀 How to Run

1. Download or clone this repository.
2. Open the project folder.
3. Rename:

```text
Basic calculator.txt
```

to:

```text
calculator.html
```

4. Open `calculator.html` in a web browser.
5. Enter two numbers.
6. Click an operation button.

---

## 🎯 What I Learned

This project helped me understand the basics of:

* HTML input fields
* HTML buttons
* JavaScript functions
* `onclick`
* `getElementById()`
* Getting values from inputs
* `Number()`
* Basic mathematical operators
* `innerHTML`
* Connecting HTML with JavaScript

---

## 💡 Example

```text
First Number: 2
Second Number: 8

[ ADD ] [ SUBTRACT ] [ MULTIPLY ] [ DIVIDE ]

Result: 10
```

---

## 👨‍💻 Author

**Nikhil Kumar Sharma**

B.Tech CSE — AI/ML

---

## 📄 License

This project was created for **learning and educational purposes**.
