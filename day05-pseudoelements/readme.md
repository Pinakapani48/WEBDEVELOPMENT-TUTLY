
**# Day 05 - Pseudo Elements

## Overview

This project introduces CSS pseudo-elements and advanced selectors. It demonstrates how to style specific parts of an element, insert content before and after elements, and select particular list items using structural pseudo-classes.

---

## Live Demo

🔗 **View Project**

https://pinakapani48.github.io/WEBDEVELOPMENT-TUTLY/day05-pseudoelements/

---

## Project Structure

```text
day05-pseudoelements
│
├── index.html
├── styles.css
└── README.md
```

---

## Features Implemented

* Unordered lists
* Paragraphs
* External CSS
* List styling
* Structural pseudo-classes
* Pseudo-elements
* Content insertion before elements
* Content insertion after elements
* First-letter styling
* First-line styling
* Margins
* Font sizing

---

# Concepts Learned

## 1. Unordered List

Used to display a collection of items.

### Syntax

```html
<ul>
    <li>Item-1</li>
    <li>Item-2</li>
</ul>
```

---

## 2. Paragraph

Used to display textual content.

### Syntax

```html
<p>
    Paragraph content goes here.
</p>
```

---

## 3. List Style Type

Removes the default bullets.

### Syntax

```css
list-style-type: none;
```

---

## 4. List Style Position

Controls the position of list markers.

### Syntax

```css
list-style-position: outside;
```

---

## 5. nth-child() Pseudo-Class

Selects elements according to their position.

### Syntax

```css
li:nth-child(even){
    color: green;
}
```

### Purpose

Styles even-numbered list items.

---

## 6. last-child Pseudo-Class

Selects the last child element.

### Syntax

```css
li:last-child{
    color: gold;
}
```

### Purpose

Styles the last list item differently.

---

# Pseudo Elements

Pseudo-elements are used to style specific parts of an element or insert content before or after an element.

General Syntax

```css
selector::pseudo-element{
    property: value;
}
```

---

## 7. ::before

Inserts content before an element.

### Syntax

```css
li::before{
    content: '👉';
    margin-right: 10px;
}
```

### Purpose

Adds an arrow emoji before every list item.

---

## 8. ::after

Inserts content after an element.

### Syntax

```css
li::after{
    content: '😊';
}
```

### Purpose

Adds a smile emoji after every list item.

---

## 9. ::first-letter

Styles the first letter of an element.

### Syntax

```css
.para1::first-letter{
    font-weight: bold;
    font-size: 4rem;
    color: crimson;
}
```

### Purpose

Creates a decorative first letter similar to magazines and newspapers.

---

## 10. ::first-line

Styles only the first line of an element.

### Syntax

```css
.para2::first-line{
    color: blueviolet;
}
```

### Purpose

Highlights the first line of a paragraph.

---

## 11. Font Size

Controls the size of text.

### Syntax

```css
font-size: 2rem;
```

---

## 12. Margin

Creates spacing around elements.

### Syntax

```css
margin: 10px 50px;

margin-top: 100px;
```

---

## Files Used

### index.html

Contains:

* Unordered lists
* List items
* Paragraphs

### styles.css

Contains:

* List styling
* Structural pseudo-classes
* Pseudo-elements
* Font properties
* Margins

---

## Outcome

By completing this project, I learned how to use CSS pseudo-elements to style specific parts of elements and insert content dynamically. I also explored structural pseudo-classes such as `:nth-child()` and `:last-child()`, which helped me understand how to target elements based on their position in the document.

---

## Repository

**Repository:** WEBDEVELOPMENT-TUTLY

**Project:** Day 05 - Pseudo Elements

**Author:** Pinaka Pani Vinay Kumar
**
