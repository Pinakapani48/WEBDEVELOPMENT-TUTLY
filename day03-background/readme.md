
# Day 03 - Internal Page Navigation and Layout

## Overview

This project demonstrates how to create a simple single-page website using HTML and CSS. The webpage represents a Full Stack Web Development roadmap containing Frontend and Backend technologies. Clicking on any technology hyperlink automatically scrolls the page to its corresponding content section using internal page navigation.

---

## Live Demo

🔗 **View Project**

https://pinakapani48.github.io/WEBDEVELOPMENT-TUTLY/day03-background/

---

## Project Structure

```text
day03-background
│
├── index.html
├── styles.css
└── README.md
```

---

## Features Implemented

- Main heading section
- Frontend Technologies section
- Backend Technologies section
- Unordered lists
- Hyperlinks
- Internal page navigation
- Content sections for each technology
- Background colors
- Text colors
- Padding
- Margins
- Font sizes
- Center alignment
- Classes and IDs

---

# Concepts Learned

## 1. Div

Used to divide the webpage into multiple sections.

### Syntax

```html
<div class="mainheading">
    <h1>Full Stack Web Development</h1>
</div>
```

---

## 2. Unordered List

Used to organize technologies.

### Syntax

```html
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
```

---

## 3. Hyperlinks

Used to create links.

### Syntax

```html
<a href="#html">HTML</a>
```

---

## 4. IDs

Used as destinations for hyperlinks.

### Syntax

```html
<div class="html" id="html">
```

---

## 5. Internal Page Navigation

Clicking a hyperlink automatically scrolls to the respective section.

### Syntax

```html
<a href="#html">HTML</a>

<div class="html" id="html">
```

---

## 6. Universal Selector

Applied to all elements.

### Syntax

```css
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
```

---

## 7. Background Color

Used to change the background color.

### Syntax

```css
background-color: skyblue;
```

---

## 8. Text Color

Used to change the text color.

### Syntax

```css
color: aliceblue;
```

---

## 9. Text Alignment

Used to align text.

### Syntax

```css
text-align: center;
```

---

## 10. Padding

Used to create space inside an element.

### Syntax

```css
padding: 80px;
```

---

## 11. Margin

Used to create space outside an element.

### Syntax

```css
margin-top: 50px;
margin-top: 300px;
```

---

## 12. Font Size

Used to change text size.

### Syntax

```css
font-size: 1.5rem;
font-size: 2rem;
```

---

## 13. Text Decoration

Used to remove the underline from hyperlinks.

### Syntax

```css
text-decoration: none;
```

---

## 14. RGB Colors

Used to specify colors using RGB values.

### Syntax

```css
color: rgb(42, 68, 42);
```

---

## Flow of the Webpage

```text
Main Heading
      ↓

Frontend Technologies
HTML
CSS
JavaScript
ReactJS

Backend Technologies
Node
Express
MongoDB

      ↓

HTML Content Section

      ↓

CSS Content Section

      ↓

JavaScript Content Section

      ↓

ReactJS Content Section

      ↓

NodeJS Content Section

      ↓

ExpressJS Content Section

      ↓

MongoDB Content Section
```

---

## Internal Navigation Flow

```text
<a href="#html">
            ↓
id="html"

<a href="#css">
            ↓
id="css"

<a href="#js">
            ↓
id="js"

<a href="#rjs">
            ↓
id="rjs"

<a href="#node">
            ↓
id="node"

<a href="#express">
            ↓
id="express"

<a href="#db">
            ↓
id="db"
```

---

## Outcome

By completing this project, I learned how to divide a webpage into sections using `div`, organize content using unordered lists, apply styling using CSS, and implement internal page navigation using hyperlinks and IDs. These concepts are fundamental for building structured and interactive web pages.

---

## Repository

**Repository:** WEBDEVELOPMENT-TUTLY

**Project:** Day 03 - Internal Page Navigation and Layout

**Author:** Pinaka Pani Vinay Kumar
