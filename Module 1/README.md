# Phase 1: Module 1 - Detailed 3-Week Study Schedule

**Total Time Allotment:** 3 Weeks (15 sessions x 3 hours = 45 hours)
**Start Date:** July 29, 2025

---

## Week 1: Web Foundations, HTML, CSS & Git Basics

**Goal:** Understand how the web works, solidify HTML and CSS for layout, and establish a foundational Git workflow.

### Session 1 (3 hours): How the Web Works & HTML Fundamentals

* **Learning (2 hrs):** Dive into Client-Server Architecture, HTTP/HTTPS (request methods, status codes), DNS, IP Addresses, Browsers.
    * **Resource:** MDN Web Docs - "How the web works"
    * **Resource:** MDN Web Docs - "Introduction to HTML"
* **Practice (1 hr):** Set up your development environment (VS Code, Live Server extension). Create a basic `index.html` with correct structure (`<!DOCTYPE>`, `<html>`, `<head>`, `<body>`), main headings, paragraphs, lists.
* **Git:** Initialize a new Git repository for your learning (`git init`).

### Session 2 (3 hours): Semantic HTML & Basic CSS

* **Learning (2 hrs):** Explore semantic HTML5 tags (`<header>`, `<nav>`, `<main>`, `<footer>`, `<section>`, `<article>`), their purpose, and importance for accessibility/SEO. Introduction to CSS: linking CSS, basic selectors (element, class, ID), properties (color, font-size, background), Box Model.
    * **Resource:** MDN Web Docs - "HTML elements reference"
    * **Resource:** MDN Web Docs - "CSS basics"
* **Practice (1 hr):** Refactor your `index.html` with semantic tags. Create a `style.css` and style your page using basic selectors and box model properties.
* **Git:** `git add .`, `git commit -m "Add basic HTML and CSS structure"`.

### Session 3 (3 hours): CSS Layout - Flexbox Essentials

* **Learning (2 hrs):** Deep dive into Flexbox. Understand `display: flex`, `flex-direction`, `justify-content`, `align-items`, `flex-wrap`, `flex-grow`, `flex-shrink`, `flex-basis`. Practice common layout patterns.
    * **Resource:** CSS-Tricks - "A Complete Guide to Flexbox"
    * **Resource:** Flexbox Froggy (game) for interactive practice.
* **Practice (1 hr):** Create a simple navigation bar and a product grid layout using Flexbox.
* **Git:** Commit your Flexbox practice code.

### Session 4 (3 hours): CSS Layout - Grid Introduction & Responsive Design

* **Learning (2 hrs):** Introduction to CSS Grid (basic concepts: `display: grid`, `grid-template-columns`, `grid-template-rows`). Understand Responsive Design principles: viewport meta tag, fluid layouts (`%`, `vw/vh`), and basic media queries.
    * **Resource:** CSS-Tricks - "A Complete Guide to CSS Grid"
    * **Resource:** Grid Garden (game) for interactive practice.
    * **Resource:** MDN Web Docs - "Responsive design"
* **Practice (1 hr):** Combine Flexbox and basic Grid for a simple responsive page layout. Implement a basic media query to adjust layout for smaller screens.

### Session 5 (3 hours): Git & GitHub Hands-on / Mini-Project 1 Kickoff

* **Learning (1 hr):** Deeper dive into Git: `git log`, `git diff`, `git branch`, `git checkout`. Introduction to GitHub: creating a repository, `git remote add origin`, `git push`, `git pull`.
    * **Resource:** GitHub Guides - "Hello World"
    * **Resource:** Pro Git book (online) - Chapters 1-2.
* **Practice (2 hrs):** Mini-Project 1: Personal Portfolio Page (Static).
    * Create a new GitHub repository for this project.
    * Build a simple, semantic HTML page about yourself with sections for About, Skills, and Contact Info.
    * Style it cleanly with CSS, using Flexbox for sections.
    * Ensure it's basic responsive.
    * **Crucially:** Practice committing frequently (`git add .`, `git commit -m "..."`) and pushing to GitHub regularly (`git push origin main`).

---

## Week 2: JavaScript Fundamentals & Asynchronous JS Introduction

**Goal:** Master core JavaScript syntax, control flow, functions, scope, and begin understanding asynchronous concepts crucial for web development.

### Session 6 (3 hours): JS Basics - Variables, Data Types, Operators, Control Flow

* **Learning (2 hrs):** Review `let`, `const`, `var`. All data types (primitives, objects). Arithmetic, comparison, logical operators. `if/else`, `switch`, `for`, `while` loops.
    * **Resource:** JavaScript.info - "The JavaScript language" (Sections on variables, data types, operators, loops, conditional operators).
* **Practice (1 hr):** Solve simple JavaScript challenges on Codewars (8 kyu/7 kyu) or freeCodeCamp using these concepts (e.g., number checks, string manipulations, simple loops).

### Session 7 (3 hours): JS Functions, Scope & Arrays

* **Learning (2 hrs):** Function declarations vs. expressions. Introduction to Arrow Functions (syntax). Understanding global, function, and block scope. Introduction to Arrays and common array methods (`push`, `pop`, `shift`, `unshift`, `length`).
    * **Resource:** JavaScript.info - "Functions", "Arrow functions", "Scope", "Arrays".
* **Practice (1 hr):** Write functions with different scope examples. Practice array manipulation (e.g., finding min/max in array, filtering, mapping simple arrays).

### Session 8 (3 hours): Objects, DOM Manipulation & Higher-Order Functions

* **Learning (2 hrs):** Objects (properties, methods). DOM Manipulation basics: `getElementById`, `querySelector`, `addEventListener`, `textContent`, `innerHTML`, `classList`. Introduction to Higher-Order Array Methods (`forEach`, `map`, `filter`, `reduce`).
    * **Resource:** JavaScript.info - "Objects", "Document", "Array methods".
* **Practice (1 hr):** Create a simple HTML page with buttons that change text/styles using DOM manipulation. Practice `map`, `filter`, `forEach` on arrays of objects.

### Session 9 (3 hours): Asynchronous JavaScript - Callbacks & Introduction to Promises

* **Learning (2 hrs):** Understand synchronous vs. asynchronous execution. Callbacks for async operations (e.g., `setTimeout`, `setInterval`). The concept of "callback hell." Introduction to Promises: pending, fulfilled, rejected states. Basic `new Promise()`, `.then()`, `.catch()`.
    * **Resource:** MDN Web Docs - "Asynchronous JavaScript"
    * **Resource:** JavaScript.info - "Promises" (start with basic concepts).
* **Practice (1 hr):** Write simple functions that return Promises. Use `setTimeout` wrapped in a Promise.

### Session 10 (3 hours): Git Branching & Merging / Mini-Project 2 Kickoff

* **Learning (1 hr):** More advanced Git: `git status` output detail, `git remote show origin`, `git merge <branch-name>`. Practice branching workflows (feature branches).
    * **Resource:** Git Branching Strategy guides (e.g., Git Flow or GitHub Flow basics).
* **Practice (2 hrs):** Mini-Project 2: Interactive Quote Generator.
    * Set up a new GitHub repository.
    * HTML/CSS: Basic layout for a quote display area and a "New Quote" button.
    * JavaScript: Use `fetch` (with a simple callback or initial Promise) to get quotes from a public API (e.g., `https://api.quotable.io/random`). Display the quote and author.
    * **Crucially:** Practice creating feature branches for new functionality (e.g., `feature/fetch-quotes`), committing on them, and merging back to `main`. Push all branches to GitHub.

---

## Week 3: Modern JavaScript Deep Dive & Module Completion

**Goal:** Master modern ES6+ features, advanced asynchronous patterns (`async/await`), and complete mini-projects to solidify all Module 1 concepts.

### Session 11 (3 hours): ES6+ Modern Features - Destructuring, Spread/Rest

* **Learning (2 hrs):** Deep dive into Destructuring Assignment (arrays, objects, function parameters). Master Spread (`...`) and Rest (`...`) Operators for arrays and objects.
    * **Resource:** JavaScript.info - "Destructuring assignment", "Spread syntax".
* **Practice (1 hr):** Refactor existing JavaScript code or solve new challenges extensively using destructuring, spread, and rest operators.

### Session 12 (3 hours): Asynchronous JavaScript - Async/Await Mastery

* **Learning (2 hrs):** In-depth into `async` functions and `await` keyword. How it simplifies Promise chains. Error handling with `try...catch` in `async/await`. `Promise.all()`, `Promise.race()`.
    * **Resource:** MDN Web Docs - "`async function`"
    * **Resource:** JavaScript.info - "Async/await"
* **Practice (1 hr):** Implement the Quote Generator (Mini-Project 2) again, but refactor the API fetching logic to exclusively use `async/await`. Practice `Promise.all()` with multiple simultaneous fetch calls to different simple APIs.

### Session 13 (3 hours): ES6+ Modern Features - Modules, Classes, and Utilities

* **Learning (2 hrs):** Understanding ES Modules (`import`/`export`) for organizing code. ES6 Classes (constructors, methods, inheritance). Introduction to Optional Chaining (`?.`) and Nullish Coalescing (`??`).
    * **Resource:** JavaScript.info - "Modules", "Classes", "Optional chaining", "Nullish coalescing operator".
* **Practice (1 hr):** Convert your Quote Generator (or another mini-project) into a modular structure using `import`/`export`. Experiment with a simple class (e.g., a `Person` class).

### Session 14 (3 hours): Mini-Project 3: Vanilla JS To-Do List

* **Practice (3 hrs):** Mini-Project 3: Dynamic To-Do List (Vanilla JavaScript).
    * Create a new GitHub repository.
    * HTML: Input field, "Add" button, list (`<ul>`) to display tasks.
    * CSS: Style it cleanly and responsively.
    * JavaScript:
        * Add new tasks (from input to list).
        * Mark tasks as complete/incomplete (toggle class).
        * Delete tasks.
        * (Bonus) Store tasks in `localStorage` so they persist on refresh.
    * **Crucially:** Apply all the modern JS concepts learned: arrow functions, destructuring, spread operator, modular design (if applicable), proper event handling, error handling. Use Git consistently.

### Session 15 (3 hours): Module 1 Review & Final Touches

* **Review (2 hrs):**
    * Go through your Mini-Projects. Identify areas where you can refactor or improve.
    * Revisit any concepts you found challenging.
    * Review common Git commands and GitHub workflow.
    * Spend time looking at other simple HTML/CSS/JS projects on GitHub to get inspiration and see different approaches.
* **Preparation (1 hr):** Ensure all your mini-projects are pushed to their respective GitHub repositories. Prepare a brief summary of your learning for this module.

---

## Tips for Success in Module 1:

* **Active Learning:** Don't just read or watch videos. Code along, pause, experiment, break things, and fix them.
* **Debug Relentlessly:** Use your browser's **Developer Tools** (Console, Elements, Sources tabs) extensively to understand what your code is doing.
* **Ask Questions:** If you get stuck for more than 30 minutes on a specific coding problem, reach out! Describe the problem, what you've tried, and what you expect to happen.
* **Breaks:** Take short breaks within each 3-hour session.
* **Consistency:** Stick to your 5 sessions/week as much as possible. Consistency beats cramming.
* **Don't Rush:** If a concept takes longer to grasp, allow yourself that time. The foundation is key.