# Calculator (Task 2)

A simple, responsive calculator built with HTML, TailwindCSS (via CDN), and vanilla JavaScript. It supports mouse and keyboard input, basic arithmetic operations, delete, clear, percentage, sign toggle, and decimal handling.

## Features
- **Basic operations**: add, subtract, multiply, divide
- **Utility**: AC (clear), DEL (backspace), % (percent), ± (toggle sign)
- **Decimal support** and safe formatting for display
- **Keyboard support**: numbers, operators, Enter, Backspace, Delete, %, .
- **Responsive UI** using TailwindCSS CDN

## File Structure
- `calculator.html` — Main app file (UI + JS).
- `README.md` — This documentation.

## How to Run
1. Open `calculator.html` directly in a modern browser (Chrome, Edge, Firefox, Safari).
2. Ensure you have internet connectivity for TailwindCSS and Google Fonts CDNs.

## Keyboard Shortcuts
- `0-9` — Enter digits
- `.` — Decimal
- `+`, `-`, `*`, `/` — Operators
- `Enter` or `=` — Equals
- `Backspace` — Delete last digit
- `Delete` — Clear all
- `%` — Percent

## Notes / Troubleshooting
- If you see unexpected behavior, check that `calculator.html` contains **only one** HTML document. Remove any content that appears after the first closing `</html>`.
- Division by zero shows `NaN`/`Error` behavior depending on the section of code; current implementation prevents crashes.
- Tailwind and fonts load from CDNs; if you’re offline, the page will still work but styling/fonts may differ.

## Customization
- Fonts: Controlled via Google Fonts import in `calculator.html` (families: `Outfit`, `Space Mono`).
- Colors/Styles: Tweak the small CSS block or Tailwind utility classes in `calculator.html`.

## License
This project is for learning/demo purposes.
