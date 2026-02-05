# Browser Rendering

## What is Browser Rendering
Browser rendering is the process of converting HTML, CSS, and JavaScript into a visual webpage that users can see and interact with.

---

## High Level Flow
- Parse HTML(DOM)
- Parse CSS
- Combine DOM + CSS → Render Tree
- Execute JavaScript

---

## HTML Parsing

- First, the browser receives the HTML file from the server. It reads the code line-by-line. As it reads, it converts the tags into objects called "Nodes." It connects these nodes to create a tree structure called the DOM.

---

## CSS Parsing

- While building the stucture, the browser also downloads the CSS files. It reads through the style rules to figure out what color should be used, how big a font should be , and what margins to use.

---

## Render Tree Creation

- Now, the browser combines the structure(DOM) and the styles(CSS) into one called the Render Tree.

---

## JavaScript Execution
- JavaScript is executed by the JS engine, changes in DOM can trigger reflow and repaint and blocking the scripts can stop rendering

---

## Why Browser Rendering Matters
- Impacts page performance
- Affects user experience
- Helps write optimized front-end code
