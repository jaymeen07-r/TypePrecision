# TypePrecision

A strict typing test built for practice — focused on **character-level validation**, **controlled input flow**, and **real-world developer prompts**.

---

## 🎯 Purpose

This project is not a typing game or productivity tool.
It is a **practice system** to improve:

* Input handling logic
* State management under real-time constraints
* UI feedback precision
* Edge-case handling in user interaction

---

## ⚙️ Core Features

### 🔒 Strict Typing Engine

* Character-by-character validation
* **No forward movement on incorrect input**
* User must fix errors before continuing

### ⌫ Controlled Backspace

* Allows correction of previous characters
* Prevents skipping ahead or bypassing validation

### 🚫 Input Integrity

* Paste disabled
* Prevents cheating or bypassing typing flow

### 🎨 Visual Feedback

* Correct input → normal text
* Incorrect input → **red highlight**
* Active cursor → precise character tracking

### 🧠 Developer-Oriented Prompts

Instead of random words, the system uses prompts like:

* "design scalable notification system"
* "optimize database queries for performance"
* "build reusable component architecture"

---

## 🧩 Engineering Focus Areas

This project intentionally targets:

* Real-time input validation
* Efficient DOM/UI updates
* Cursor synchronization
* Handling rapid keystrokes
* Preventing invalid state transitions

---

## 🏗️ Project Scope

* Frontend-only application
* No backend, authentication, or persistence
* Built purely for **logic and UI precision practice**

---

## 🚀 Getting Started

```bash
git clone https://github.com/your-username/typeprecision.git
cd typeprecision
```

Open `index.html` in your browser
(or run with a local dev server)

---

## 📁 Suggested Structure

```
typeprecision/
 ├── index.html
 ├── style.css
 ├── script.js
 └── prompts.js
```

---

## ⚠️ Constraints (By Design)

* No autocomplete or prediction
* No skipping words
* No leniency on errors
* Accuracy over speed

---

## 🔍 Future Experiments (Optional)

* Difficulty scaling based on mistakes
* Categorized prompt sets (frontend / backend / system design)
* Performance metrics (WPM, accuracy tracking)
* Mobile input behavior improvements

---

## 🧠 Key Learning Outcome

This project focuses on building a **deterministic input system** where:

* Every keystroke is validated
* State transitions are controlled
* UI reflects logic instantly and accurately

---

## 📄 License

MIT License
