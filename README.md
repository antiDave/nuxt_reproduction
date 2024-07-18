# nuxt_reproduction
Reproduce the Nuxt Card Cool Hover Effect
This project advances the work done by <a href="https://github.com/dimar-hanung">dimar-hanung</a> and demonstrates a hover effect for cards using pure HTML, CSS, and JavaScript. The effect includes a radial gradient background that follows the mouse movement when it gets close to or enters a card. From the previous work we havemade it work with standard html, css, and js.

Features
Responsive 3-column grid layout
Hover effect with a radial gradient background
Mouse proximity effect for dynamic background gradient positioning.

How to Use
Clone or Download the Repository

You can clone the repository using Git or download the ZIP file.

bash
Copy code
git clone <repository-url>
Open the HTML File

Open the index.html file in any modern web browser.

Interact with the Cards

Move your mouse over the cards to see the hover effect with the dynamic background gradient.

Code Overview
The HTML file includes inline CSS and JavaScript to achieve the desired effect. No external libraries or preprocessors are required.

HTML Structure
The main container is a <div> with a background and padding.
Inside the container, there is a <main> element with a heading and a <section> for the grid layout.
Each card is a <div> with classes to apply styles and the hover effect.
CSS Styling
Custom styles are applied for the background, text, grid layout, and hover effects.
The radial gradient background is dynamically positioned based on mouse movement.
JavaScript Functionality
The script listens for the mousemove event and updates the CSS custom properties for the gradient position.
