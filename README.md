# Pixel Art Coordinate Challenge

A browser-based pixel art editor that teaches programming concepts through an interactive 12x12 grid canvas. Write JavaScript code to programmatically create pixel art with real-time visual feedback.

## Features

- **Interactive 12x12 Grid** — Click and hover to see coordinates, watch your code draw in real-time
- **Built-in Code Editor** — Syntax highlighting for JavaScript with live execution
- **Animation Support** — Create animated pixel art with adjustable speed controls
- **Share Functionality** — Generate compressed URLs and QR codes to share your creations
- **Built-in Examples** — Learn from 6 pre-made examples including patterns, shapes, and animations

## Getting Started

No installation required. Simply open `index.html` in any modern web browser.

```bash
# Clone the repository
git clone <repository-url>
cd pixel-art

# Open in browser
open index.html
```

Or deploy to any static web host — the entire application is a single HTML file.

## API Reference

### Functions

| Function | Description |
|----------|-------------|
| `fill(row, col, color)` | Colors a cell at the specified coordinates |
| `clear()` | Clears the entire grid |
| `sleep(ms)` | Pauses execution for animations (async) |

### Available Colors

`red`, `orange`, `yellow`, `lime`, `green`, `cyan`, `blue`, `purple`, `magenta`, `pink`, `white`, `gray`

### Example

```javascript
// Draw a diagonal line
for (let i = 0; i < 12; i++) {
  fill(i, i, 'cyan');
  await sleep(100);
}
```

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd + Enter` | Run code |

## Browser Support

Works on all modern browsers including Chrome, Firefox, Safari, and Edge.

## License

MIT
