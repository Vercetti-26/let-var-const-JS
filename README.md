# var vs let vs const — The JavaScript Variable Bible

> A beautifully designed, single-page deep dive into JavaScript's three variable keywords — built with pure HTML & CSS, zero dependencies.

![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-f7c948?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-pure-e34f26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-custom-264de4?style=flat-square&logo=css3&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-4ecdc4?style=flat-square)

---

## 📖 About

This is a single-file educational webpage that explains everything a JavaScript developer needs to know about `var`, `let`, and `const` — from their history to how they differ in scoping, hoisting, and practical usage.

Designed to feel like a premium dev blog post, the page is fully self-contained in one `index.html` file with hand-crafted CSS and syntax-highlighted code blocks.

---

## 🧠 What's Covered

- **History** — Why `let` and `const` were introduced in ES6 (2015) and what problems `var` caused
- **Scope** — Function scope vs block scope with real examples
- **Hoisting** — How all three keywords are hoisted differently, and what the Temporal Dead Zone (TDZ) is
- **Re-declaration vs Reassignment** — What's allowed, what throws errors, and why
- **const with Objects & Arrays** — The most common misconception explained clearly
- **Full Comparison Table** — Side-by-side view of every key difference
- **Modern Best Practices** — A decision framework for when to use each keyword
- **Real-world code examples** — Practical patterns used in production JavaScript

---

## 🗂️ Project Structure

let-var-const-JS/
├── index.html # The entire app — content + styles in one file
└── README.md

text

---

## 🚀 Getting Started

No build tools, no npm, no dependencies. Just open the file:


git clone https://github.com/Vercetti-26/let-var-const-JS.git
cd let-var-const-JS
open index.html   # or just double-click it
Or view it live if deployed on GitHub Pages.

🎨 Design Highlights
Dark theme with a custom color system — var in red, let in teal, const in yellow

JetBrains Mono for all code blocks with manual syntax highlighting

Syne + Lora typefaces for a premium editorial feel

Responsive layout with keyword cards, comparison table, timeline, callout boxes, and decision framework

Zero external JS — pure semantic HTML and CSS

📋 Key Takeaway
var	let	const
Scope	Function / Global	Block	Block
Hoisting	✅ → undefined	⚠️ TDZ	⚠️ TDZ
Re-declaration	✅	❌	❌
Reassignment	✅	✅	❌
Use in modern JS	❌ Legacy	✅ When mutating	✅ Default choice
Rule of thumb: Default to const. Use let when you need to reassign. Never use var in new code.

🏷️ Tags
#JavaScript #ES6 #WebDev #Frontend #100DaysOfCode #LearnToCode

👤 Author
Made by Vercetti-26 — part of a JavaScript deep dives series.
