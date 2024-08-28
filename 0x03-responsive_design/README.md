# Responsive Design Project

## Overview

This project is part of the ALX Front-End curriculum, focusing on responsive design principles. The main objective is to create a responsive hero section on a webpage that adjusts gracefully across different screen sizes.

## Project Structure

- **01-index.html**: The HTML file contains the structure of the webpage, including the hero section.
- **01-styles.css**: The CSS file includes the styles necessary to make the webpage responsive, specifically focusing on the hero section.

## Task Details

### Hero Section Styling

- The hero section background has been adjusted to improve its visibility and alignment across various devices.
- Key properties that were updated:
  - **background-position**: `65% 8rem`
  - **background-size**: `90rem auto`
  - **min-height**: `35vh` for the inner section to ensure it occupies the correct amount of space.

### File Overview

- **01-index.html**: Contains the main structure of the hero section, with a header element wrapping the hero content.
- **01-styles.css**: Defines the styling for the hero section and other global styles.

### HTML Structure

```html
<header class="section-hero">
    <div class="section-inner">
        <h1>Welcome to the Hero Section</h1>
        <p>This is the hero section of the homepage.</p>
    </div>
</header>

