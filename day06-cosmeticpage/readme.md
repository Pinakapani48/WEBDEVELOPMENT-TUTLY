# Day 06 - Cosmetic Page

## Overview

This project introduces background images, Flexbox layout, image styling, and hover effects. It demonstrates how to create a visually appealing webpage with a hero section, formatted paragraphs, and a responsive image gallery.

---

## Live Demo

🔗 **View Project**

https://pinakapani48.github.io/WEBDEVELOPMENT-TUTLY/day06-cosmeticpage/

---

## Project Structure

```text
day06-cosmeticpage
│
├── index.html
├── styles.css
├── lamp.webp
├── lotion.jpg
├── perfume.jpg
├── shampoo.webp
└── README.md
```

---

## Features Implemented

* Background image
* Headings
* Paragraphs
* Text indentation
* First-letter styling
* Flexbox layout
* Image sizing
* Object fitting
* Rounded corners
* Hover effects
* Box shadows
* Transitions
* Margins and padding

---

# Concepts Learned

## 1. Background Image

Used to place an image behind an element.

### Syntax

```css
.header{
    background-image: url(./lamp.webp);
}
```

---

## 2. Background Size

Controls the size of the background image.

### Syntax

```css
background-size: 100% 700px;
```

### Purpose

Stretches the image to cover the desired area.

---

## 3. Text Indentation

Creates space at the beginning of the first line of a paragraph.

### Syntax

```css
text-indent: 150px;
```

---

## 4. ::first-letter Pseudo-Element

Styles the first letter of an element.

### Syntax

```css
p::first-letter{
    font-weight: bold;
    color: orange;
    font-size: 2.5rem;
}
```

### Purpose

Creates a decorative effect similar to magazines and newspapers.

---

## 5. Flexbox

Used to arrange elements in rows or columns.

### Syntax

```css
.images{
    display: flex;
    justify-content: space-between;
}
```

### Purpose

Places the three images evenly across the page.

---

## 6. object-fit

Controls how an image fits inside its container.

### Syntax

```css
object-fit: cover;
```

### Purpose

Maintains image proportions while filling the specified dimensions.

---

## 7. Border Radius

Rounds the corners of elements.

### Syntax

```css
border-radius: 15px;
```

### Purpose

Creates smooth and visually pleasing image corners.

---

## 8. Transition

Adds smooth animation effects.

### Syntax

```css
transition: all 0.3s ease;
```

### Purpose

Makes hover effects appear smoothly.

---

## 9. Transform

Changes the size, position, or rotation of elements.

### Syntax

```css
transform: scale(1.05);
```

### Purpose

Enlarges the image slightly when hovered.

---

## 10. Box Shadow

Creates shadow effects around elements.

### Syntax

```css
box-shadow: 0 0 30px rgb(3, 102, 141);
```

### Purpose

Produces a glowing effect around images.

---

## 11. Margin and Padding

Creates spacing around and inside elements.

### Syntax

```css
margin: 30px;

padding-left: 100px;
padding-right: 100px;
```

---

## Files Used

### index.html

Contains:

* Hero section
* Headings
* Paragraph
* Image gallery

### styles.css

Contains:

* Background image styling
* Typography styles
* Pseudo-elements
* Flexbox layout
* Image styling
* Hover effects
* Box shadows
* Transitions

---

## Outcome

By completing this project, I learned how to create visually attractive webpages using background images, Flexbox, pseudo-elements, and image effects. I also explored transitions, transforms, and box shadows to make the webpage interactive and aesthetically pleasing.

---

## Repository

**Repository:** WEBDEVELOPMENT-TUTLY

**Project:** Day 06 - Cosmetic Page

**Author:** Pinaka Pani Vinay Kumar
