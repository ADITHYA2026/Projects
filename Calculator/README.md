---

# 🧮 JavaScript Calculator

A fully functional, responsive calculator web app built using **HTML**, **CSS**, and **JavaScript**. It supports basic arithmetic operations and is styled with custom hover effects and modern typography.

---

## 📌 Step 1: Project Overview

* **🎯 Objective**: Implement a basic calculator with arithmetic functionality and clear visual interaction.
* **🛠 Tech Stack**:

  * HTML5
  * CSS3
  * JavaScript
  * Google Fonts (Monoton)
* **✨ Key Features**:

  * Arithmetic operations: `+`, `-`, `×`, `÷`, `%`
  * Special functions: Clear, Backspace, Double Zero (00)
  * Decimal point support
  * Responsive and accessible layout
  * Interactive hover effects and animation

---

## 🧱 Step 2: HTML Structure

* **Setup**:

  * Standard `<!DOCTYPE html>`, meta tags, and external font & CSS links
  * Page title: `"CALCULATOR ~ BY ADITYA PRATHI"`

* **Elements**:

  * Calculator title
  * Display screen using `<input>`
  * Grid of buttons:

    * Digits `0-9`, operators `+ - * / %`
    * `C`, `←`, `=`, `.`, `00`

---

## 🎨 Step 3: CSS Styling

* **Global Styling**:

  * Background: light cyan
  * Font: `'Monoton'`, cursive
  * Reset default margins/paddings

* **Layout**:

  * Centered using CSS Grid
  * 500x500px calculator box with border and rounded corners
  * Positioned absolutely with shadow

* **Display Screen**:

  * 88% width, 100px height
  * Font size: 50px
  * Border radius: 50px
  * Right-aligned text

* **Buttons**:

  * Size: 110px × 60px
  * Dark green background, black border
  * White background on hover
  * Transition duration: 0.5s

---

## ⚙️ Step 4: JavaScript Functionality

* **Functions**:

  ```js
  function Solve(val) { /* Appends value */ }
  function Result() { /* Uses eval() to evaluate */ }
  function Clear() { /* Clears the input */ }
  function Back() { /* Deletes last character */ }
  ```

* **Operations**:

  * Real-time input updates
  * `=` evaluates the full expression
  * `C` and `←` handle editing

---

## 🌟 Step 5: Key Features

| Feature          | Description                                |
| ---------------- | ------------------------------------------ |
| Basic Arithmetic | Handles `+`, `-`, `*`, `/`, `%`, `.`, `00` |
| Editing          | Clear all or delete one character          |
| UI Feedback      | Button hover animations                    |
| Readability      | Large screen, well-spaced layout           |

---

## 🔧 Step 6: Potential Improvements

* **Security**:

  * Avoid `eval()`; use expression parser
  * Validate inputs

* **Functionality**:

  * Memory buttons (M+, M-, MR, MC)
  * Scientific calculator features
  * Keyboard input support

* **Design**:

  * Add Dark Mode
  * Error handling (e.g., divide by zero)
  * Animated button press feedback

* **Code Quality**:

  * Use event delegation for button listeners
  * Introduce state management
  * Add unit tests

---

## ☁️ Step 7: Deployment

* **Recommended Platforms**:

  * GitHub Pages
  * Netlify / Vercel
  * AWS S3 Static Site

* **Tips**:

  * Minify CSS/JS
  * Optimize for performance
  * Use CSS variables for easy theming

---

## ✅ Step 8: Conclusion

* Demonstrates core **JavaScript DOM and eval logic**
* Uses **CSS Grid and transitions** effectively
* Fully responsive and accessible calculator
* Great starting point for more advanced calculator versions

---

## ▶️ Demo Instructions

1. **🧪 Local**:

   * Open `index.html` in any modern browser
   * Test all calculator functions

2. **🌐 Online**:

   * Deploy HTML, CSS, JS files on GitHub Pages or Netlify
   * Ensure correct file paths for fonts and styles
   * Works without backend setup

---
