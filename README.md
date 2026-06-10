# Metallic Plate Generator

This project is a browser-based utility designed to turn plain code snippets into clean, aesthetic metallic-style graphics. It features real-time editing and one-click high-resolution PNG exports.

## Key Features
- **Live Editing:** Click to edit or paste your code directly into the plate.
- **Dynamic Resizing:** The plate adapts its width and height to fit your code perfectly.
- **High-Quality Export:** Uses `html-to-image` to generate crisp, high-resolution PNGs with drop-shadow effects.
- **Responsive:** Designed to work across different screen sizes.

## How it works
1. **The Plate:** A styled `div` with a `clip-path` to create the custom diagonal corners.
2. **The Editor:** A `contenteditable` div allows for instant text input without needing a heavy backend.
3. **The Snapshot:** The `html-to-image` library handles the complex rendering of shadows and gradients into a single image file.

## Technologies Used
- HTML5
- CSS3 (Tailwind-integrated for utility styling)
- JavaScript
- [html-to-image](https://github.com/bubkoo/html-to-image)

## How to use
Simply open the site, paste your code, and click the **Download Image** button.
