# Rich Text Editor

An easy-to-use, lightweight Rich Text Editor built with plain HTML, CSS and JavaScript. It provides common text-formatting controls (bold, lists, alignment, font, colors, headings, undo/redo, links) in a clean, minimal UI so you can drop the editor into any static site or prototype.

![Editor Screenshot](./Screenshot%202024-04-26%20104425.png)

---

## Features

- Bold, superscript, subscript
- Ordered and unordered lists
- Undo / Redo
- Create / remove links
- Text alignment (left, center, right, justify)
- Indent / Outdent
- Heading formats (H1–H6)
- Font family and font size selection
- Font color and highlight color
- Keyboard-friendly and lightweight (no external frameworks required)

## Files

- `index.html` — the editor markup and toolbar
- `style.css` — styles for the editor UI
- `script.js` — editor behavior using `document.execCommand`
- `Screenshot 2024-04-26 104425.png` — project screenshot

## Usage

1. Clone or download the repository:

```bash
git clone https://github.com/BinaryVortex/Rich-Text-Editor.git
```

2. Open `index.html` in your browser (double-click or use a local server).

3. Click inside the editing area and use the toolbar to format text. To add a link, click the link button and enter a URL (protocol optional).

## Notes

- This editor uses the (now-deprecated) `document.execCommand` API for simplicity and broad browser support. For production or advanced features consider replacing it with a modern, maintained rich-text engine (e.g., ProseMirror, Slate, Quill) or using browser-supported standardized APIs as they evolve.

- The screenshot file name contains spaces — when linking or referencing the image on other platforms, ensure the filename is properly URL-encoded or renamed.

## Contributing

Contributions are welcome! If you want to add features or fix issues:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Open a pull request describing your changes.

## License

This project is provided "as-is" — add a license file if you want to set terms for reuse.

## Acknowledgements

- Font Awesome for toolbar icons (loaded from CDN in `index.html`).

