#  Calculator :– 

Welcome to the web-based calculator built with **pure JavaScript, HTML, and CSS**. This calculator is designed to handle **basic arithmetic, advanced mathematical operations, trigonometry, logarithms, and more!**  

---

## 🌟 Features  
✔️ **Secure Computation** – No `eval()`, preventing security vulnerabilities.  
✔️ **Accurate Order of Operations** – Implements **Infix-to-Postfix** conversion for proper precedence.  
✔️ **Advanced Math Functions** – Includes factorial, square roots, exponents, logarithms, and trigonometry.  
✔️ **Radians & Degrees Support** – Easily toggle between the two for trigonometric calculations.  
✔️ **Error Handling** – Prevents incorrect results for cases like `tan(90°)` or `log(0)`.  

---

## 🎯 Why This Approach?  

Instead of using JavaScript's built-in functions directly, this calculator follows a **structured approach** to ensure correctness and flexibility.  

### 1️⃣ **No `eval()`** :- 
🔹 The calculator **parses the input manually**, preventing security risks.  
🔹 It **tokenizes the expression** and processes it step by step.  

### 2️⃣ **Infix to Postfix Conversion – Ensuring Correct Order of Operations**  
🔹 Expressions like `5 + 3 × 2` should give **11**, not **16**.  
🔹 Uses **Postfix (Reverse Polish Notation)** with a **stack-based approach** to evaluate expressions accurately.  

### 3️⃣ **Custom Implementations for Factorials & Functions**  
🔹 Factorials (`n!`) are calculated **iteratively** instead of relying on a math library.  
🔹 Prevents incorrect results for `0^0` or `tan(90°)`.  

---

## 📜 Installation & Usage  

### Clone the Repository  
```sh
git clone https://github.com/vraj62023/calculator1.git
