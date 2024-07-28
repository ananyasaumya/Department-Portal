# Portfolio Website

This portfolio website is a simple, elegant, and responsive webpage designed to showcase your work, skills, and experience. It features a modern design with a toggleable light and dark mode for better user experience.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [File Structure](#file-structure)
4. [How to Use](#how-to-use)
5. [Customization](#customization)
6. [Technologies Used](#technologies-used)
7. [License](#license)

## Introduction

This project is a personal portfolio website built with HTML, CSS, and JavaScript. It includes sections for your header, about information, timeline, portfolio, blog, and contact details. The theme of the website can be toggled between light and dark mode for better accessibility and user preference.

## Features

- **Responsive Design**: The website is fully responsive and works well on different devices and screen sizes.
- **Theme Toggle**: Users can switch between light and dark mode.
- **Interactive Controls**: Navigation through different sections using interactive buttons.
- **CSS Variables**: Easily customizable colors and styles using CSS variables.

## File Structure

```plaintext
Portfolio/
│
├── index.html
├── styles.css
├── script.js
└── README.md
```

### index.html

The main HTML file contains the structure of the webpage, including the header, sections for content, and buttons for navigation and theme toggling.

### styles.css

The CSS file includes all the styles for the website. It defines colors, layouts, and responsive design, as well as the light and dark mode themes.

### script.js

The JavaScript file contains the logic for the interactive controls and theme toggle functionality.

### README.md

The README file (this document) provides an overview of the project, its features, and instructions on how to use and customize the website.

## How to Use

1. **Download or Clone the Repository**: 
   ```bash
   git clone https://github.com/your-username/portfolio.git
   ```
2. **Open the HTML File**: Open `index.html` in your preferred web browser to view the website.

3. **Navigate Through Sections**: Use the control buttons on the right side to navigate through different sections of the website.

4. **Toggle Theme**: Click the theme button at the top right corner to switch between light and dark mode.

## Customization

### Changing Content

- **HTML**: Update the content inside `index.html` to reflect your personal information, skills, experience, projects, and contact details.
- **CSS**: Modify the styles in `styles.css` to customize the look and feel of the website. You can change colors, fonts, layouts, etc.

### Changing Colors and Styles

The CSS uses variables for easy theming. You can find and modify these variables at the beginning of the `styles.css` file:

```css
:root {
    --color-primary: #191d2b;
    --color-secondary: #27AE60;
    --color-white: #FFFFFF;
    --color-black: #000;
    --color-grey0: #f8f8f8;
    --color-grey-1: #dbe1e8;
    --color-grey-2: #b2becd;
    --color-grey-3: #6c7983;
    --color-grey-4: #454e56;
    --color-grey-5: #2a2e35;
    --color-grey-6: #12181b;
}
```

For the light mode, you can modify the variables inside the `.light-mode` class:

```css
.light-mode {
    --color-primary: #FFFFFF;
    --color-secondary: #F56692;
    --color-white: #454e56;
    --color-black: #000;
    --color-grey0: #f8f8f8;
    --color-grey-1: #6c7983;
    --color-grey-2: #6c7983;
    --color-grey-3: #6c7983;
    --color-grey-4: #454e56;
    --color-grey-5: #f8f8f8;
    --color-grey-6: #12181b;
}
```

### Adding New Sections

To add a new section, follow these steps:

1. **HTML**: Add a new section block in `index.html`:

    ```html
    <div id="new-section" class="section">Content for New Section</div>
    ```

2. **CSS**: Define the styles for the new section in `styles.css` if needed.

3. **JavaScript**: Add a new control button in `index.html` with the corresponding `data-id`:

    ```html
    <button class="control" data-id="new-section">New Section</button>
    ```

## Technologies Used

- **HTML**: For the structure of the website.
- **CSS**: For styling the website.
- **JavaScript**: For interactivity and theme toggling.
