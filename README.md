# Modern Task Management System 

A high-performance, vanilla JavaScript application designed for persistent task tracking. This project demonstrates clean architecture, DOM manipulation, and state persistence via the Browser's LocalStorage API.

##  Overview

This application serves as a robust solution for personal productivity. Unlike basic tutorials, this version features sanitized data entry, an intuitive "edit-in-place" workflow, and a refined UI inspired by modern SaaS design systems.

### Key Features
*   **Persistent State:** Data survives page refreshes and browser restarts using `localStorage`.
*   **CRUD Architecture:** Full implementation of Create, Read, Update, and Delete operations.
*   **Input Sanitization:** Custom RegEx logic to ensure HTML ID safety and prevent DOM breakage from special characters.
*   **Responsive Modal Workflow:** Interactive dialog system for form handling and data loss prevention.
*   **Optimized UI:** A mobile-first, accessible interface with smooth transitions and clear feedback.

##  Tech Stack

*   **HTML5:** Semantic markup and native `<dialog>` components.
*   **CSS3:** Custom properties (CSS variables), Flexbox, and advanced UI styling.
*   **JavaScript (ES6+):** Functional programming patterns, arrow functions, and array methods (`map`, `filter`, `splice`).

##  Installation & Usage

To run this project locally, no specialized environment or build tools (like Node.js) are required.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/sackeytech/modern-todo-app.git](https://github.com/sackeytech/modern-todo-app.git)

2. **Navigate to the directory:**
    cd modern-todo-app

3. **Launch the application:**
Simply open index.html in any modern web browser.  

 ##  What I Learned

While building this project, I solidified my understanding of several core JavaScript concepts:
* **Data-to-UI Syncing:** Keeping the JavaScript array (`taskData`) perfectly in sync with the DOM elements rendered on the screen.
* **Regular Expressions (Regex):** Using `/[^A-Za-z0-9\-\s]/g` to sanitize user input and prevent broken HTML structures.
* **The `this` Keyword:** Passing specific DOM elements into functions to target the correct task card for editing and deleting.
* **Form Data Handling:** Capturing input values and managing the transition between "Add" and "Edit" states using a single, dynamic form.

##  Interface Preview

### Dashboard View
![Main Dashboard](to%20do%20list%20dashboard.png)

### Task Entry Workflow
![New Task Modal](the%20to%20do%20list%20data.png)




---
*Coded  by Caleb Nyanney Sackey*
