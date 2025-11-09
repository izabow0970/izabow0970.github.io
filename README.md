# Izaiah Bowers — Photography Portfolio

This project is a fully responsive photography portfolio website built with **HTML5** and **CSS3**.  
It showcases my portrait and lifestyle work, with a modern, Apple/SpaceX-inspired dark theme.

Live site: https://izabow0970.github.io/

---

## Features

- **Semantic HTML5 structure**
  - `<header>`, `<main>`, `<section>`, `<footer>`, `<nav>`, `<figure>`, `<table>`, etc.
- **Hero section**
  - Full-bleed background image with overlay text and call-to-action buttons.
- **Main content sections**
  - **About** – brief introduction to me as a photographer.
  - **Contact** – link to a dedicated contact page with a form.
  - **Projects** – summary table of sample projects with images.
- **Projects table**
  - Uses `<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, `<colgroup>`, `<col>`, `<tr>`, `<th>`, and `<td>`.
  - Columns 1 and 3 are styled using `<colgroup>` / `<col>`.
- **Responsive layout**
  - Flexbox for navigation, main content layout, and contact form.
  - Media queries for phone, tablet, and desktop breakpoints.
- **CSS transitions and interactivity**
  - Smooth hover transitions on navigation links.
  - Section card “zoom” on hover (transform: `scale(1.02)` with transition).
  - Contact form inputs and button with hover/focus transitions.
- **Accessibility touches**
  - Skip to content link.
  - Clear heading structure and descriptive alt text for images.

---

## Technologies Used

- **HTML5**
- **CSS3**
  - Flexbox
  - Media queries
  - Transitions and transforms
- (Optional) **JavaScript**  
  - `js/main.js` is used for small helpers like setting the current year in the footer and highlighting nav links.

---

## Project Structure

```bash
.
├── index.html        # Homepage (hero, About, Contact, Projects table)
├── about.html        # About page
├── projects.html     # Projects gallery (2x2 image layout)
├── contact.html      # Contact page with form
├── css
│   └── style.css     # Global styles, layout, responsive rules
├── js
│   └── main.js       # Small JS helpers
└── images            # Hero image and project photos (1.png, 3.png, etc.)
