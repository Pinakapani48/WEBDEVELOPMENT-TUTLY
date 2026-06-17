
# 03.2 - Vide Ocean

## Overview

This project introduces background images and button styling. It demonstrates how to create a landing page with a full-page background image, large headings, centered content, and interactive buttons with hover effects.

---

## Live Demo

🔗 **View Project**

https://pinakapani48.github.io/WEBDEVELOPMENT-TUTLY/03.2-vide-ocean/

---

## Project Structure

```text
03.2-vide-ocean
│
├── index.html
├── styles.css
├── water.avif
└── README.md
```

---

## Features Implemented

* Background image
* Headings
* Hyperlinks
* Button styling
* Center alignment
* Margins
* Borders
* Hover effects
* Box shadows
* Transform property

---

# Concepts Learned

## 1. Background Image

Used to place an image behind an element.

### Syntax

```css
body{
    background-image: url(./water.avif);
}
```

### Purpose

Adds a visually appealing image to the webpage background.

---

## 2. Background Size

Controls the size of the background image.

### Syntax

```css
background-size: 100%;
```

### Purpose

Stretches the image across the page.

---

## 3. Text Alignment

Used to align text horizontally.

### Syntax

```css
text-align: center;
```

### Purpose

Places headings and buttons in the center of the page.

---

## 4. Margin

Creates spacing around elements.

### Syntax

```css
margin: 300px 200px 50px 200px;

margin-top: 50px;
```

### Purpose

Provides proper spacing between elements.

---

## 5. Border

Creates an outline around elements.

### Syntax

```css
border: 5px solid aliceblue;
```

### Purpose

Makes hyperlinks appear like buttons.

---

## 6. Hyperlinks as Buttons

Anchor elements can be styled to resemble buttons.

### Syntax

```html
<a href="" class="link1">Download</a>

<a href="" class="link2">Docs</a>
```

### Purpose

Creates clickable navigation buttons.

---

## 7. Hover Pseudo-Class

Applies styles when the mouse cursor is placed over an element.

### Syntax

```css
a:hover{
    transform: scale(1.05);
    box-shadow: 2px -2px 20px grey;
}
```

### Purpose

Provides interactive effects when users hover over buttons.

---

## 8. Transform Property

Changes the appearance of an element.

### Syntax

```css
transform: scale(1.05);
```

### Purpose

Slightly enlarges the button on hover.

---

## 9. Box Shadow

Creates a shadow effect around elements.

### Syntax

```css
box-shadow: 2px -2px 20px grey;
```

### Purpose

Adds a glowing effect to the buttons.

---

## Files Used

### index.html

Contains:

* Main heading
* Subheading
* Download button
* Docs button

### styles.css

Contains:

* Background image styling
* Typography styles
* Margin properties
* Border properties
* Hyperlink styling
* Hover effects
* Transform property
* Box shadows

---

## Outcome

By completing this project, I learned how to create a simple landing page using a background image and centered content. I also explored how hyperlinks can be styled as buttons and enhanced with hover effects, scaling, and shadow effects to create a more interactive user experience.

---

## Repository

**Repository:** WEBDEVELOPMENT-TUTLY

**Project:** 03.2 - Vide Ocean

**Author:** Pinaka Pani Vinay Kumar
