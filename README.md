# 🌐 JS University Labs

This repository contains a collection of **HTML/CSS/JavaScript lab assignments**, each organized as a separate task.

👉 **Live Demo:**  
https://vikavl.github.io/js-uni-labs/

---

# 📸 Preview

![Preview](titulka.jpg)

---

# 📚 Tasks Overview

Each folder represents a separate lab:

## 📚 Labs Overview

| Lab | Description | Link |
|-----|------------|------|
| Lab 1 | Basic JavaScript calculations (circle area, triangle hypotenuse) | [Open](https://vikavl.github.io/js-uni-labs/1/1.html) |
| Lab 2 | Event handling & geometry (triangle area, distance, variable swap) | [Open](https://vikavl.github.io/js-uni-labs/2/1.html) |
| Lab 3 | Conditional logic (max values, triangle validation, coordinate quadrant) | [Open](https://vikavl.github.io/js-uni-labs/3/1.html) |
| Lab 4 | DOM manipulation & image interaction (swap, zoom, menu effects) | [Open](https://vikavl.github.io/js-uni-labs/4/1.html) |
| Lab 5 | Forms & dynamic styling (UI control, user анкета) | [Open](https://vikavl.github.io/js-uni-labs/5/1.html) |
| Lab 6 | Complex form processing (course selection & cost calculator) | [Open](https://vikavl.github.io/js-uni-labs/6/1.html) |
| Lab 7 | UI customization & mini apps (table styling, shopping calculator) | [Open](https://vikavl.github.io/js-uni-labs/7/1.html) |
| Lab 8 | Algorithms & number processing (reverse, lucky tickets, divisors) | [Open](https://vikavl.github.io/js-uni-labs/8/1.html) |
| Lab 9 | Date processing & real-world logic (week number, zodiac, calendar) | [Open](https://vikavl.github.io/js-uni-labs/10/1.html) |
| Lab 10 | Text processing (word count, replacement, formatting) | [Open](https://vikavl.github.io/js-uni-labs/10_B/1.html) |
___ 

## 🧪 Lab 1 — Basic JavaScript Calculations

📍 [Open Lab 1](https://vikavl.github.io/js-uni-labs/1/1.html)

This lab demonstrates simple JavaScript-based computations:

### 🔹 Features
- Calculate **circle area** from radius  
- Calculate **hypotenuse** using two triangle sides  
- Uses basic:
  - HTML forms  
  - JavaScript functions  
  - event handling (`onChange`)  

### 💡 Example Tasks
- Input radius → compute area  
- Input two sides → compute hypotenuse

___

## 🧪 Lab 2 — JavaScript Events & Geometry

📍 [Open Lab 2](https://vikavl.github.io/js-uni-labs/2/1.html)

This lab focuses on **JavaScript event handling** and **mathematical computations** using user input.

---

### 🔹 Task 2.2 — Triangle Area (focus event)

📍 [Open](https://vikavl.github.io/js-uni-labs/2/1.html)

- Computes the **area of a triangle** using coordinates of three points  
- Uses a formula based on determinants  
- Triggered by **`onFocus` event**

📌 Concepts:
- coordinate geometry  
- event handling (`focus`)  
- form input processing  

---

### 🔹 Task 2.3 — Distance to Origin (select event)

📍 [Open](https://vikavl.github.io/js-uni-labs/2/2.html)

- Computes distance from a point to origin:  
  √(x² + y²)  
- Triggered by **`onSelect` event**

📌 Concepts:
- Euclidean distance  
- event handling (`select`)  
- numeric parsing  

---

### 🔹 Task 2.4 — Swap Variables (blur event)

📍 [Open](https://vikavl.github.io/js-uni-labs/2/3.html)

- Swaps values of two variables  
- Triggered by **`onBlur` event**

📌 Concepts:
- variable manipulation  
- event handling (`blur`)  

---

### 🎯 Key Learning Outcomes

- Understanding different **JavaScript events**:
  - `focus`
  - `select`
  - `blur`
- Working with **form inputs**
- Implementing **mathematical logic in JS**
- Building interactive UI behavior without libraries

___

## 🧪 Lab 3 — Conditional Logic & Decision Making

📍 [Open Lab 3](https://vikavl.github.io/js-uni-labs/3/1.html)

This lab focuses on implementing **conditional statements in JavaScript** to solve logic-based problems.

---

### 🔹 Task 3.2 — Count Maximum Values

📍 [Open](https://vikavl.github.io/js-uni-labs/3/1.html)

- Finds the **maximum value** among 5 numbers  
- Counts how many times this maximum appears  

📌 Concepts:
- comparison operators  
- conditional statements (`if`)  
- working with multiple inputs  

---

### 🔹 Task 3.3 — Triangle Existence Check

📍 [Open](https://vikavl.github.io/js-uni-labs/3/2.html)

- Checks if a triangle can exist based on 3 sides  
- Uses triangle inequality rule:
  - a + b > c  
  - a + c > b  
  - b + c > a  

📌 Concepts:
- logical conditions  
- validation of input  
- mathematical rules in programming  

---

### 🔹 Task 3.4 — Coordinate Quadrant Detection

📍 [Open](https://vikavl.github.io/js-uni-labs/3/3.html)

- Determines which **quadrant** a point (x, y) belongs to  

📌 Concepts:
- coordinate system  
- multi-condition branching  
- decision logic  

---

### 🎯 Key Learning Outcomes

- Writing **conditional logic in JavaScript**
- Handling **multiple input values**
- Implementing **real-world mathematical conditions**
- Understanding how decision-making works in programs

___

## 🧪 Lab 4 — DOM Manipulation & Image Interaction

📍 [Open Lab 4](https://vikavl.github.io/js-uni-labs/4/1.html)

This lab focuses on **interactive image manipulation using JavaScript and DOM properties**.

---

### 🔹 Task 4.2 — Image Selection & Swap

📍 [Open](https://vikavl.github.io/js-uni-labs/4/1.html)

- Select one of three images by entering its number  
- The selected image is swapped with another image  

📌 Concepts:
- DOM access via `document.images`  
- working with image sources (`src`)  
- user input → dynamic UI update  

---

### 🔹 Task 4.3 — Image Zoom Effect

📍 [Open](https://vikavl.github.io/js-uni-labs/4/2.html)

- Images increase in size when hovered  
- Return to original size when mouse leaves  

📌 Concepts:
- mouse events:
  - `onmouseover`
  - `onmouseout`  
- dynamic manipulation of:
  - `width`
  - `height`  

---

### 🔹 Task 4.4 — Interactive Menu with Hover Indicator

📍 [Open](https://vikavl.github.io/js-uni-labs/4/3.html)

- Horizontal image menu  
- Displays an arrow indicator when hovering over menu items  

📌 Concepts:
- DOM navigation (`getElementById`, `children`)  
- event handling (`mouseover`, `mouseout`)  
- dynamic content updates  

---

### 🎯 Key Learning Outcomes

- Working with the **DOM API**
- Handling **mouse events**
- Creating **interactive UI elements**
- Manipulating images dynamically
- Building simple **visual effects without libraries**

___

## 🧪 Lab 5 — Forms & Dynamic Styling

📍 [Open Lab 5](https://vikavl.github.io/js-uni-labs/5/1.html)

This lab focuses on **user input handling, form processing, and dynamic style manipulation using JavaScript**.

---

### 🔹 Task 5.2 — Dynamic Line Position & Size

📍 [Open](https://vikavl.github.io/js-uni-labs/5/1.html)

- Controls the position and size of a horizontal line (`<hr>`)  
- Uses radio buttons to:
  - resize the line  
  - move it (top, center, bottom)  

📌 Concepts:
- DOM manipulation (`getElementById`)  
- modifying CSS properties:
  - `width`
  - `marginTop`
  - `marginLeft`  
- handling form events (`onClick`)  

---

### 🔹 Task 5.3 — User Form (Anketa)

📍 [Open](https://vikavl.github.io/js-uni-labs/5/2.html)

- Collects user data:
  - gender  
  - age  
  - marital status  
- Displays results using an alert message  

📌 Concepts:
- working with form inputs  
- radio buttons  
- conditional logic  
- string construction  

---

### 🎯 Key Learning Outcomes

- Handling **user input via forms**
- Dynamically updating **CSS styles with JavaScript**
- Using **radio buttons and form controls**
- Building simple interactive UI behavior

___

## 🧪 Lab 6 — Form Processing & Cost Calculation

📍 [Open Lab 6](https://vikavl.github.io/js-uni-labs/6/1.html)

This lab implements a **course selection system** where users choose parameters and the script calculates the total cost.

---

### 🔹 Task — Course Cost Calculator

- Users can select:
  - course type (OOP, Algorithms, Programming)  
  - duration  
  - language of instruction  
  - reporting format  

- The system calculates:
  - cost of each selected course  
  - total cost of all selected options  

---

### 📊 Functionality

- Each option has an assigned value (price)  
- Selected options are combined dynamically  
- Results are displayed in a text area  

---

### 📌 Concepts

- working with **checkbox inputs**  
- iterating over form elements  
- using arrays for aggregation  
- dynamic calculation based on user input  
- updating UI (`textarea`)  

---

### 🎯 Key Learning Outcomes

- Handling **complex forms with multiple parameters**  
- Implementing **calculation logic across multiple inputs**  
- Structuring data using arrays  
- Building a simple **interactive pricing system**

___

## 🧪 Lab 7 — UI Customization & Interactive Systems

📍 [Open Lab 7](https://vikavl.github.io/js-uni-labs/7/1.html)

This lab focuses on **dynamic UI customization and interactive data processing using JavaScript**.

---

### 🔹 Task 7.2 — Table Style Customizer

📍 [Open](https://vikavl.github.io/js-uni-labs/7/1.html)

- Allows users to customize:
  - table background color  
  - background images  
  - individual cell styling  
- Supports manual color input  

📌 Concepts:
- DOM manipulation (`getElementById`)  
- dynamic CSS updates  
- working with:
  - `background`
  - `background-image`  
- user-driven UI customization  

---

### 🔹 Task 7.3 — Shopping Cart Calculator

📍 [Open](https://vikavl.github.io/js-uni-labs/7/2.html)

- Simulates a simple shopping system  
- Users select:
  - product  
  - quantity  
- Calculates total purchase cost  

📌 Concepts:
- `switch` statement  
- cumulative sum calculation  
- working with `select` inputs  
- event-driven updates  

---

### 🎯 Key Learning Outcomes

- Building **interactive UI configuration tools**
- Dynamically modifying **styles and layout**
- Using `switch-case` for structured logic  
- Creating simple **real-world applications (shopping/cart logic)**

___

## 🧪 Lab 8 — Algorithms & Number Processing

📍 [Open Lab 8](https://vikavl.github.io/js-uni-labs/8/1.html)

This lab focuses on implementing **classic algorithmic problems using JavaScript**, working with loops, arithmetic operations, and number manipulation.

---

### 🔹 Task 8.2 — Reverse a Number

📍 [Open](https://vikavl.github.io/js-uni-labs/8/1.html)

- Reverses a given natural number  
- Example: 123 → 321  

📌 Concepts:
- loops (`while`)  
- modulo operation (`%`)  
- integer division  

---

### 🔹 Task 8.3 — Lucky Tickets

📍 [Open](https://vikavl.github.io/js-uni-labs/8/2.html)

- Counts all **"lucky" six-digit numbers**  
- A number is lucky if:
  - sum of first 3 digits = sum of last 3 digits  

📌 Concepts:
- iteration over large ranges  
- string manipulation (`split`)  
- digit extraction  

---

### 🔹 Task 8.4 — Divisors of a Number

📍 [Open](https://vikavl.github.io/js-uni-labs/8/3.html)

- Finds all divisors of a given number  

📌 Concepts:
- loops (`for`)  
- divisibility (`%`)  
- building output dynamically  

---

### 🎯 Key Learning Outcomes

- Implementing **classic algorithmic problems**
- Working with **loops and conditions**
- Understanding **number decomposition**
- Developing **problem-solving skills**

___

## 🧪 Lab 9 — Date Processing & Real-World Logic

📍 [Open Lab 9](https://vikavl.github.io/js-uni-labs/10/1.html)

This lab focuses on **working with dates and implementing real-world logic using JavaScript**.

---

### 🔹 Task 9.2 — Week Number in Year

📍 [Open](https://vikavl.github.io/js-uni-labs/10/1.html)

- Calculates the **week number of the year** for a given date  
- Input format: `YYYY.MM.DD`  

📌 Concepts:
- working with `Date` object  
- time difference calculation  
- converting days → weeks  

---

### 🔹 Task 9.3 — Zodiac Sign

📍 [Open](https://vikavl.github.io/js-uni-labs/10/2.html)

- Determines a person's **zodiac sign** based on birth date  

📌 Concepts:
- date comparison  
- conditional logic  
- mapping date ranges to categories  

---

### 🔹 Task 9.4 — Chinese Zodiac Year

📍 [Open](https://vikavl.github.io/js-uni-labs/10/3.html)

- Determines the **Chinese zodiac year** (animal + color)  
- Based on a 60-year cycle  

📌 Concepts:
- modular arithmetic  
- циклічні обчислення (cycles)  
- combining multiple logical conditions  

---

### 🎯 Key Learning Outcomes

- Working with **dates in JavaScript**
- Implementing **real-world logic systems**
- Understanding **cyclical patterns (calendar systems)**
- Building user-facing tools with meaningful outputs

___

## 🧪 Lab 10 — Text Processing & String Manipulation

📍 [Open Lab 10](https://vikavl.github.io/js-uni-labs/10_B/1.html)

This lab focuses on **processing and transforming text using JavaScript**, including word counting, replacement, and formatting.

---

### 🔹 Task 10.2 — Word Count

📍 [Open](https://vikavl.github.io/js-uni-labs/10_B/1.html)

- Counts the number of words in user input  
- Handles multiple spaces between words  

📌 Concepts:
- string splitting (`split`)  
- regular expressions (`/\s+/`)  
- array length calculation  

---

### 🔹 Task 10.3 — Word Replacement

📍 [Open](https://vikavl.github.io/js-uni-labs/10_B/2.html)

- Replaces all occurrences of a word **K** with another word **L**  

📌 Concepts:
- array transformation (`map`)  
- conditional replacement  
- string reconstruction (`join`)  

---

### 🔹 Task 10.4 — Remove Extra Spaces

📍 [Open](https://vikavl.github.io/js-uni-labs/10_B/3.html)

- Replaces multiple consecutive spaces with a single space  

📌 Concepts:
- regular expressions (`/  +/g`)  
- text normalization  
- string replacement  

---

### 🎯 Key Learning Outcomes

- Working with **strings and text data**
- Using **regular expressions (RegExp)**
- Applying **array methods for transformations**
- Building simple **text-processing utilities**
