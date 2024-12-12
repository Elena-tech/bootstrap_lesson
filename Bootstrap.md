# Lesson: Introduction to Bootstrap

## Objectives

By the end of this lesson, students will:

1. Understand what Bootstrap is and why it is useful.
2. Learn how to include Bootstrap in a project.
3. Explore key Bootstrap components and utilities for building responsive websites.
4. Create a simple responsive webpage using Bootstrap.

---

## What is Bootstrap?

Bootstrap is a popular open-source front-end framework for building responsive, mobile-first websites quickly and efficiently. It provides pre-designed components like navigation bars, buttons, modals, and a grid system for layout, allowing developers to save time on styling and focus on functionality.

### Why Use Bootstrap?

1. **Responsive Design**: Built to look great on all devices, from phones to desktops.
2. **Pre-designed Components**: Includes pre-styled elements like buttons, cards, and forms.
3. **Customization**: Easily customize styles to fit your design.
4. **Community Support**: Large community with extensive documentation and tutorials.

---

## How to Include Bootstrap in Your Project

### Option 1: Use a Content Delivery Network (CDN)

Add the following `<link>` and `<script>` tags to your HTML file's `<head>`:

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
```

### Option 2: Download Bootstrap Files

1. Visit [getbootstrap.com](https://getbootstrap.com) and download the Bootstrap files.
2. Add the CSS and JS files to your project folder.
3. Link them in your HTML:

```html
<link rel="stylesheet" href="path-to-bootstrap/bootstrap.min.css">
<script src="path-to-bootstrap/bootstrap.bundle.min.js"></script>
```

---

## Bootstrap Grid System

Bootstrap uses a **12-column grid system** to create responsive layouts. Content is placed inside rows and columns.

### Basic Example:

```html
<div class="container">
    <div class="row">
        <div class="col">Column 1</div>
        <div class="col">Column 2</div>
        <div class="col">Column 3</div>
    </div>
</div>
```

### Key Classes:

1. **`container`**: A wrapper for the grid system.
2. **`row`**: Defines a row in the grid.
3. **`col`**: Defines columns. You can specify sizes like `col-6` (6/12 of the width).
4. **Breakpoints**: `col-sm-`, `col-md-`, `col-lg-`, `col-xl-`, `col-xxl-` for responsive design.

### Responsive Example:

```html
<div class="container">
    <div class="row">
        <div class="col-md-6">Half-width on medium screens and larger</div>
        <div class="col-md-6">Half-width on medium screens and larger</div>
    </div>
</div>
```

---

## Common Bootstrap Components

### 1. Navigation Bar

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">Brand</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
            <li class="nav-item">
                <a class="nav-link" href="#">Home</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">About</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Contact</a>
            </li>
        </ul>
    </div>
</nav>
```

### 2. Buttons

```html
<button class="btn btn-primary">Primary Button</button>
<button class="btn btn-secondary">Secondary Button</button>
<button class="btn btn-success">Success Button</button>
```

### 3. Cards

```html
<div class="card" style="width: 18rem;">
    <img src="image.jpg" class="card-img-top" alt="Card image">
    <div class="card-body">
        <h5 class="card-title">Card Title</h5>
        <p class="card-text">Some quick example text to build on the card title.</p>
        <a href="#" class="btn btn-primary">Go somewhere</a>
    </div>
</div>
```

### 4. Forms

```html
<form>
    <div class="mb-3">
        <label for="email" class="form-label">Email address</label>
        <input type="email" class="form-control" id="email">
    </div>
    <div class="mb-3">
        <label for="password" class="form-label">Password</label>
        <input type="password" class="form-control" id="password">
    </div>
    <button type="submit" class="btn btn-primary">Submit</button>
</form>
```

---

## Utilities and Helpers

### Spacing

- `m-3`: Adds margin
- `p-3`: Adds padding

### Text

- `text-center`: Centers text
- `text-uppercase`: Transforms text to uppercase

### Display

- `d-none`: Hides an element
- `d-block`: Displays an element

---

## Hands-on Activity

Create a simple responsive webpage using the components covered:

1. Include Bootstrap via CDN.
2. Add a navigation bar with links.
3. Create a 2-column layout using the grid system.
4. Add a card component with a button.
5. Add a form for user input.

---

## Additional Resources

- [Official Bootstrap Documentation](https://getbootstrap.com)
- [Bootstrap Grid Builder](https://bootstrap.build)

---

## Homework

1. Create a responsive portfolio page using Bootstrap.
2. Experiment with different components and utilities.
3. Share your work in the next class for feedback.

---

### Questions?

Feel free to ask during the session or reach out via email!


