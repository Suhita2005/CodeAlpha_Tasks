# Image Gallery (Task 1)

A responsive image gallery built with HTML, TailwindCSS (via CDN), and lightweight CSS transitions. It features hover animations, overlay captions, and a modern grid layout.

## Features
- **Responsive grid** that adapts to screen sizes
- **Hover interactions**: lift, scale, and shadow
- **Overlay captions** that fade in on hover
- **Smooth transitions** using CSS

## File Structure
- `gallary.html` — Main gallery page (UI and styles).
- `README.md` — This documentation.

## How to Run
1. Open `gallary.html` directly in your browser (Chrome, Edge, Firefox, Safari).
2. Ensure internet connectivity for the TailwindCSS and Google Fonts CDNs.

## Customization
- **Images**: Replace the image sources inside `gallary.html` with your own URLs/paths.
- **Captions**: Update the overlay text for each gallery item.
- **Grid**: Adjust Tailwind grid classes (e.g., `grid-cols-2 md:grid-cols-3 lg:grid-cols-4`).
- **Effects**: Tweak the custom CSS in the `<style>` block (e.g., `.gallery-item` and `.image-overlay`).

## Notes / Troubleshooting
- If images don’t load, check the paths/URLs used in `<img src="..." />` tags.
- If styling looks off while offline, Tailwind/Fonts may not load from CDNs; reconnect to the internet.
- The file name is `gallary.html` (note the spelling). Keep links consistent if you reference it from elsewhere.

## License
This project is for learning/demo purposes.
