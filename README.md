### Project Overview

This project is part of the **GoIT Fullstack Development Course**. The goal is to enhance the previous project by adding markup and styling for icons and decorative effects for the pages according to the layout.

## 📁 Project Structure

- The `images` folder in the project root contains all the images.
- All vector icons are compiled into a single SVG sprite `icons.svg` located in the `images` folder.
- All vector images are optimized.
- The `css` folder in the project root contains styles.
- All styles are written in one file `styles.css`.
- File names use only lowercase letters and English words. No spaces, uppercase letters, or transliteration.
- Source code is formatted using **Prettier**.
- All images and textual content are taken from the design mockup.
- All HTML pages include **modern-normalize** for consistent styling.
- Code follows the style guide provided by the course.

## 🧩 Markup Features

- All icons use vector graphics in SVG format.
- SVG icons are exported correctly as **groups**, not as individual vectors.
- All icons from the SVG sprite are included in the HTML using `<svg>` and `<use>` tags.
- Icon dimensions are taken from the design and set on the `<svg>` elements in HTML.
- Email and phone icons are added to the header contact block.
- Icons are added to:
  - Benefits section
  - Team section (social media)
  - Clients section (company logos)
  - Footer (social media links)

## 🎨 Styling & Effects

- The large background image under the header includes a dark overlay created using a layered gradient background.
- The background image does not scale beyond its original width of 1600px.
- Team cards have a persistent shadow effect.
- Portfolio cards have a hover shadow effect that applies to the entire card.
- Filter buttons (on the Portfolio page) have a shadow effect on hover and focus.
- On hover or focus, icons change to their active state (e.g., color change), if specified in the design.

## 🔧 Technologies Used

- **HTML5** for markup
- **Prettier** for code formatting
- **Squoosh** for image optimization
- **IcoMoon** for generate the SVG sprite.
- **SVGOMG** for optimize the generated SVG sprite.
- **GitHub Pages** for deployment

## 🌐 Live Page

The project is deployed via **GitHub Pages**. You can view the live version [here](https://kseniia-diak.github.io/goit-hw-04/)

## Author

**Kseniia Diak** [GitHub Profile](https://github.com/Kseniia-Diak/)
