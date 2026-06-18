# CALC_PRO ⚡ — Advanced Calculator

<div align="center">

A modern, responsive calculator built with pure HTML, CSS & JavaScript.

🔗 **Live Demo:** https://sebastinajoe.github.io/OIBSIP/Calculator/

</div>

---

## 📌 Project Overview

**CALC_PRO** is a fully functional, modern calculator application developed as part of the **Oasis Infobyte Internship Program (OIBSIP)**.

Built entirely with **vanilla HTML, CSS, and JavaScript**, the application features a sleek dark neon-purple theme, smooth animations, keyboard support, and a collapsible calculation history panel.

---

## ✨ Features

* ➕ Basic arithmetic operations (+, −, ×, ÷)
* 💯 Percentage calculation
* ± Sign toggle
* 📜 Calculation history (stores last 20 calculations)
* ⌨️ Full keyboard support
* ⌫ Backspace support
* 📱 Responsive design
* 🌙 Dark neon UI theme
* ⚠️ Division-by-zero error handling
* 🔢 Precision up to 12 significant figures

---

## 🛠️ Technologies Used

* **HTML5** — Semantic structure
* **CSS3** — Grid, Flexbox, animations, custom properties
* **JavaScript** — DOM manipulation and calculator logic
* **Google Fonts**

  * Share Tech Mono
  * Inter

---

## 📂 Project Structure

```text
OIBSIP/
├── Calculator/
│   ├── index.html
│   └── README.md
└── README.md
```

---

## 🚀 How to Run

### Option 1: View Live

🔗 https://sebastinajoe.github.io/OIBSIP/Calculator/

### Option 2: Run Locally

```bash
git clone https://github.com/sebastinajoe/OIBSIP.git
cd OIBSIP/Calculator
```

Open `index.html` in your browser.

---

## ⌨️ Keyboard Shortcuts

| Key        | Action            |
| ---------- | ----------------- |
| 0–9        | Enter digits      |
| . or ,     | Decimal point     |
| +          | Addition          |
| -          | Subtraction       |
| *          | Multiplication    |
| /          | Division          |
| Enter or = | Calculate result  |
| Backspace  | Delete last digit |
| Escape     | Clear all (AC)    |
| %          | Percentage        |

---

## 🧠 JavaScript Logic

The calculator uses four main state variables:

* `currentVal` → Current input value
* `prevVal` → Stored operand
* `operator` → Selected operation
* `shouldReset` → Controls display reset

### Core Functions

| Function          | Purpose                |
| ----------------- | ---------------------- |
| `render()`        | Updates display        |
| `inputDigit()`    | Handles number input   |
| `inputDot()`      | Adds decimal point     |
| `setOperator()`   | Stores operator        |
| `calculate()`     | Performs calculations  |
| `toggleSign()`    | Switches sign          |
| `percent()`       | Converts to percentage |
| `clear()`         | Resets calculator      |
| `addHistory()`    | Stores calculations    |
| `renderHistory()` | Displays history       |

---

## 🎨 Design Highlights

### Color Palette

| Color         | Hex Code  |
| ------------- | --------- |
| Purple Accent | `#7c3aed` |
| Cyan Accent   | `#06b6d4` |
| Background    | `#0f0f13` |
| Surface       | `#1a1a24` |
| Text          | `#f0eeff` |

### UI Features

* CSS Grid button layout
* Responsive sizing using `clamp()`
* Radial gradient background
* Neon glow effects
* Smooth transitions and animations

---

## 📋 Internship Details

| Field   | Details                                    |
| ------- | ------------------------------------------ |
| Program | Oasis Infobyte Internship Program (OIBSIP) |
| Domain  | Web Development and Designing              |
| Level   | Level 2                                    |
| Task    | Task 1 — Calculator Application            |

---

## 👩‍💻 Author

**Sebastina J**

GitHub: https://github.com/sebastinajoe

---

<div align="center">



⭐ If you like this project, consider starring the repository!

</div>
