markdown
# CampusMart - Static HTML Pages

A static, semantic HTML5 prototype for **CampusMart**, a student marketplace where university students can buy and sell second-hand textbooks, calculators, laptops, and furniture.

This project was built as part of **Lecture 1: How the Web Works, Your Developer Toolkit & HTML5** (CS554 Advanced Web Technologies).

## 📖 About the Project

Before adding styling (CSS) or interactivity (JavaScript), this project focuses entirely on **Semantic HTML5** and **Accessibility (a11y)**. The goal was to build a solid, meaningful document structure that screen readers and search engines can easily understand. 

### Features
* **`index.html`**: The home page featuring a hero section, semantic layout elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`), and a list of latest listings.
* **`sell.html`**: A fully accessible form for users to post a new item. It includes built-in HTML5 validation, grouped radio buttons, a file upload, and a data table for selling fees.
* **`about.html`**: An informational page detailing how the platform works and safety tips for campus meetups.

## 🛠️ Built With

* **HTML5** (Semantic elements, Forms, Tables, Entities)
* No CSS or JavaScript was used (as per Lecture 1 requirements).

## 📂 Project Structure

```text
campusmart-static/
├── index.html       # Homepage
├── sell.html        # "Sell an item" form
├── about.html       # About and safety info
└── README.md        # Project documentation
🚀 How to View the Pages Locally
Clone this repository or download the files.

Open the folder in Visual Studio Code.

Right-click on index.html and select "Open with Live Server" (requires the Live Server extension).

Alternatively, you can just double-click index.html to open it directly in your web browser.

✅ Project Requirements Met
Valid HTML5: All pages pass the W3C Markup Validation Service with 0 errors.

Accessibility: All form inputs are linked to <label> elements. Images have descriptive alt text. Passes Lighthouse Accessibility audit with a score of 100.

Semantic Markup: Used appropriate elements like <nav>, <main>, <article>, and <fieldset> instead of relying purely on <div>s.

Client-side Validation: Used native HTML5 attributes (required, minlength, pattern, type="email", etc.) to ensure users submit correct data.
