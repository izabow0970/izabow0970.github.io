# Izaiah Bowers — Photography Portfolio

A modern, fully responsive photography portfolio website that showcases my portrait and lifestyle work.  
The site uses a dark, cinematic aesthetic and is deployed live with GitHub Pages.

Live site: **https://izabow0970.github.io/**

---

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Features

- **Semantic HTML5 structure**
  - Uses `<header>`, `<main>`, `<section>`, `<footer>`, `<nav>`, `<figure>`, `<table>`, etc.
- **Hero section**
  - Full-width background image with overlay text and call-to-action buttons.
- **Main content sections**
  - **About** – introduction to me as a photographer.
  - **Contact** – link to a dedicated contact page with a working contact form.
  - **Projects** – overview of sample projects, including images.
- **Projects table**
  - Located in the homepage Projects section.
  - Uses `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, `<colgroup>`, `<col>`, `<tr>`, `<th>`, and `<td>`.
  - First and third columns are styled using `<colgroup>` and `<col>`.
- **Responsive layout**
  - Flexbox for the main content area, navigation menu, and contact form.
  - Media queries for phone, tablet, and desktop breakpoints.
- **CSS transitions and interactivity**
  - Smooth hover transitions on navigation links.
  - Section “zoom” on hover (`transform: scale(1.02)` with transitions).
  - Contact form fields and submit button with hover/focus transitions.
- **Accessibility**
  - Skip-to-content link.
  - Descriptive alt text for images.
  - Clear heading hierarchy and semantic markup.

---

## Technologies Used

- **HTML5**
- **CSS3**
  - Flexbox
  - Media queries
  - Transitions and transforms
- **JavaScript (optional)**
  - `js/main.js` is used for simple enhancements (e.g., dynamic year in the footer, nav highlighting).
- **GitHub Pages**
  - For live hosting of the site.
- **XAMPP** (for local server testing)

---

## Installation

You can run this project in two main ways:

### Option 1 — View Directly in a Browser (Simple Local Preview)

1. Download the repository:
   - On GitHub, click **Code → Download ZIP**.
   - Extract the ZIP file on your computer.
2. Open the project folder.
3. Double-click `index.html` (or drag it into your browser).

This is enough for a basic local preview of a static HTML/CSS site.

---

### Option 2 — Clone with Git

If you have Git installed:

```bash
# Clone the repository
git clone https://github.com/izabow0970/izabow0970.github.io.git

# Move into the project directory
cd izabow0970.github.io
