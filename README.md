---

# CSS Full Course

Welcome to the **CSS Full Course**! This repository contains all the materials and code examples you'll need to learn CSS from the ground up. Whether you're a beginner or an experienced developer, this course will help you master CSS to create beautiful, responsive websites.

## Table of Contents

1. [Course Overview](#course-overview)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Course Structure](#course-structure)
5. [Code Examples](#code-examples)
6. [Exercises](#exercises)
7. [License](#license)

---

## Course Overview

This repository is designed to guide you through CSS, starting with the basics and progressing to more advanced topics. Topics covered include:

- Introduction to CSS and styling
- CSS selectors, properties, and values
- The Box Model
- Flexbox and Grid Layout
- Positioning (relative, absolute, fixed, sticky)
- Responsive design and media queries
- Transitions and animations
- Advanced CSS techniques (pseudo-classes, pseudo-elements, etc.)
- Best practices and performance tips

Each section includes code examples and explanations to help you understand how CSS works and how to apply it to real-world projects.

---

## Prerequisites

Before starting this course, you should have:

- Basic understanding of HTML (since CSS is used to style HTML elements)
- A text editor (e.g., VS Code, Sublime Text)
- A browser to test your styles (e.g., Chrome, Firefox)

---

## Installation

### 1. Clone the repository:

```bash
git clone https://github.com/yourusername/css-full-course.git
```

### 2. Navigate to the project directory:

```bash
cd css-full-course
```

### 3. Open the project in your favorite code editor.

No installation is needed for CSS, as it's just a collection of files that you can open in any web browser.

---

## Course Structure

The course is organized by topics, and each topic contains CSS files and a brief description of the concepts. Below is the directory structure:

```
css-full-course/
│
├── 01_introduction/
│   └── index.html
│   └── style.css
├── 02_selectors/
│   └── index.html
│   └── style.css
├── 03_box_model/
│   └── index.html
│   └── style.css
├── 04_flexbox/
│   └── index.html
│   └── style.css
├── 05_grid_layout/
│   └── index.html
│   └── style.css
├── 06_positioning/
│   └── index.html
│   └── style.css
├── 07_responsive_design/
│   └── index.html
│   └── style.css
├── 08_transitions_animations/
│   └── index.html
│   └── style.css
└── 09_advanced_css/
    └── index.html
    └── style.css
```

---

## Code Examples

Here are a few basic examples to get you started with CSS:

### 1. CSS Selectors and Basic Styling (selectors/index.html and style.css)

**index.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Selectors</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Welcome to CSS Selectors</h1>
    <p>This is a paragraph styled with CSS.</p>
    <a href="#">Learn More</a>
</body>
</html>
```

**style.css**

```css
/* Universal selector for all elements */
* {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

h1 {
    color: #1a73e8;
    text-align: center;
    margin-top: 50px;
}

p {
    font-size: 18px;
    line-height: 1.5;
    margin: 20px;
}

a {
    color: #1a73e8;
    text-decoration: none;
}
```

---

### 2. The Box Model (box_model/index.html and style.css)

**index.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Box Model</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="box">
        This is a box with padding, border, and margin!
    </div>
</body>
</html>
```

**style.css**

```css
/* Box model */
.box {
    width: 300px;
    padding: 20px;
    margin: 20px;
    border: 5px solid #333;
    background-color: #e7e7e7;
    box-sizing: border-box;
}
```

---

### 3. Flexbox Layout (flexbox/index.html and style.css)

**index.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flexbox Layout</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="flex-container">
        <div class="flex-item">Item 1</div>
        <div class="flex-item">Item 2</div>
        <div class="flex-item">Item 3</div>
    </div>
</body>
</html>
```

**style.css**

```css
/* Flexbox container */
.flex-container {
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 100vh;
}

.flex-item {
    background-color: #1a73e8;
    color: white;
    padding: 20px;
    margin: 10px;
    text-align: center;
    flex: 1;
}
```

---

## Exercises

After going through the tutorials, here are some exercises to practice:

1. **Create a simple layout with a header, content section, and footer using Flexbox.**
2. **Design a responsive grid layout that adjusts the number of columns based on the screen width using CSS Grid.**
3. **Use media queries to adjust font size and layout for different screen sizes.**
4. **Create an animated button that changes color when hovered using CSS transitions.**
5. **Design a card component with a box shadow, rounded corners, and hover effects.**

---

## License

This repository is open-source and available under the MIT License. You can freely use, modify, and distribute the code, but please attribute it to the author.

---

Happy coding and designing! 🎨✨

---

