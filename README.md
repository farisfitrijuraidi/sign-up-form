# Sign-up Form

This is a sign-up form page for a fictional online service, "Odin". This project was created as part of The Odin Project's Intermediate HTML and CSS curriculum. The primary goal was to build a complex, static webpage from a design file, focusing on advanced CSS layout techniques and form styling.

---

## Features
* A clean, responsive two-column layout featuring an image sidebar and a main content section.
* An overlaid, semi-transparent logo banner on the sidebar for a modern design.
* A multi-column form layout built using CSS Flexbox, ensuring all fields are properly aligned.
* Custom font integration using `@font-face` for the logo and body text.
* Interactive form validation styling: inputs show a red border using the `:invalid` pseudo-class.
* User-friendly focus styling: inputs show a blue border and subtle box-shadow using the `:focus` pseudo-class.
* A custom-styled "Create Account" button with `:hover` and `:active` states for user feedback.

---

## What I Learned
This project was a deep dive into creating a visually complex page from a design specification. It was a practical lesson in layout techniques and the nuances of styling web forms.

Key takeaways include:
* **Advanced CSS Layout**: The core challenge was recreating the two-column page layout. I learned to use **Flexbox** to manage the main sidebar and content sections (using `flex: 1` and `flex: 2`). I then re-used Flexbox (specifically `flex-wrap: wrap`) to create the two-column layout for the form inputs themselves.
* **HTML Form Structure & Styling**: I learned the importance of structuring forms semantically using `<label for...>` and `<input id=...>` pairs. This project was also an exercise in styling form elements, applying custom `border`, `border-radius`, and `box-shadow` properties to create a clean, modern look.
* **Interactive Styling with Pseudo-classes**: A key requirement was using CSS pseudo-classes to provide user feedback without JavaScript. I implemented `:focus` to highlight the active input field (blue border/shadow) and `:invalid` to show basic validation errors (red border).
* **CSS Positioning and Overlays**: I learned how to create the semi-transparent logo banner. This involved using Flexbox to position the banner within the sidebar and applying a `background-color` with an alpha channel (e.g., `rgb(0 0 0 / 0.5)`) to let the background image show through.
* **Asset Management**: This project required importing local assets. I learned how to use the `@font-face` rule in CSS to import, name, and use custom fonts ('Norse-Bold') downloaded for the project.

---

## Acknowledgements
* This project is based on the [Sign-up Form assignment](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-sign-up-form) from The Odin Project.
* Background image by [Halie West on Unsplash](https://unsplash.com/@haliewestphoto).
* Odin logo provided by The Odin Project.