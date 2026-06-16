# Day 04 - Pseudo Classes

## Overview

This project extends the previous page navigation layout by introducing CSS pseudo-classes. Interactive effects have been applied to hyperlinks to enhance user experience. Additional spacing and padding have also been added to organize the content into separate sections.

---

## Live Demo

🔗 **View Project**

https://pinakapani48.github.io/WEBDEVELOPMENT-TUTLY/day04-pseudoclasses/

---

## Project Structure

```text
day04-pseudoclasses
│
├── index.html
├── styles.css
└── README.md
```

---

## Features Implemented

* Internal page navigation using hyperlinks
* Section linking using IDs
* Background colors
* Text colors
* Padding
* Margins
* Text alignment
* Font sizes
* Hover effect on hyperlinks
* Active state styling
* Visited link styling
* Improved page spacing and layout

---

# Concepts Learned

## 1. Internal Hyperlinks

Used to navigate between different sections of the webpage.

### Syntax

```html
<a href="#html">HTML</a>
```

---

## 2. ID Attribute

Used as the destination for internal hyperlinks.

### Syntax

```html
<div class="html" id="html">
```

---

## 3. Background Color

Used to style elements.

### Syntax

```css
background-color: skyblue;
```

---

## 4. Text Color

Used to change the color of text.

### Syntax

```css
color: aliceblue;
```

---

## 5. Text Alignment

Used to align text.

### Syntax

```css
text-align: center;
```

---

## 6. Margin

Creates spacing outside elements.

### Syntax

```css
margin-top: 50px;

margin-top: 700px;
```

---

## 7. Padding

Creates spacing inside elements.

### Syntax

```css
padding: 80px;

padding: 100px;
```

---

## 8. Font Size

Controls the size of text.

### Syntax

```css
font-size: 1.3rem;

font-size: 2rem;
```

---

## 9. Universal Selector

Applies styles to all elements.

### Syntax

```css
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
```

---

## 10. Box Sizing

Ensures padding and borders are included within the total width and height of elements.

### Syntax

```css
box-sizing: border-box;
```

---

# Pseudo Classes

Pseudo-classes are used to style elements based on their state or user interaction.

General Syntax:

```css
selector:pseudo-class{
    property: value;
}
```

---

## 11. :hover

Styles an element when the mouse pointer is placed over it.

### Syntax

```css
a:hover{
    color: aliceblue;
    background-color: rgb(42,82,42);
    padding: 2px 10px;
}
```

### Purpose

Provides visual feedback when the user hovers over a hyperlink.

---

## 12. :active

Styles an element while it is being clicked.

### Syntax

```css
a:active{
    color: orange;
}
```

### Purpose

Indicates that the hyperlink is currently being pressed.

---

## 13. :visited

Styles hyperlinks that have already been visited.

### Syntax

```css
a:visited{
    color: pink;
}
```

### Purpose

Helps distinguish previously visited links from unvisited links.

---

## Files Used

### index.html

Contains:

* Headings
* Hyperlinks
* Lists
* Content sections
* IDs

### styles.css

Contains:

* Colors
* Margins
* Padding
* Font sizes
* Pseudo-classes
* Layout styling

---

## Outcome

By completing this project, I learned how to use CSS pseudo-classes to create interactive webpages. I also improved my understanding of spacing, layout organization, and internal page navigation while enhancing the overall user experience.

---

## Repository

**Repository:** WEBDEVELOPMENT-TUTLY

**Project:** Day 04 - Pseudo Classes

**Author:** Pinaka Pani Vinay Kumar
