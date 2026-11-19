# Capstone Robotics — Bob Homepage

A responsive starter homepage for Capstone Robotics, built from the supplied visual reference, hand-drawn layout, and Bob write-up.

## Files
- `index.html` — page content and structure
- `styles.css` — layout, colors, typography, and responsive styling
- `script.js` — mobile navigation toggle
- `references/` — the two images supplied as design references

## Preview
Open `index.html` in a browser. An internet connection is needed for the Google Fonts; the page still works without them using fallback fonts.

## Add a real photo of Bob
The provided images were a visual-style reference and a layout sketch, not a photograph of Bob. The hero currently uses a simple CSS robot illustration as a placeholder.
To use a real robot photo:
1. Put the image in the `assets` folder (for example, `bob.jpg`).
2. In `index.html`, find the `<div class="robot-placeholder"...>` block.
3. Replace that block with:
   `<img class="bob-photo" src="assets/bob.jpg" alt="Bob, Capstone Robotics' first robot">`
4. Add this to `styles.css`:
   `.bob-photo { width: 100%; height: 390px; object-fit: cover; border: 1px solid rgba(198,225,165,.25); }`

## Content note
The text is based on the supplied “Bob” write-up. It does not add unprovided technical specifications.
