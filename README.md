# Clipboard Image Viewer

A single-page viewer for loading images from the browser clipboard or local files, then viewing, zooming, and panning them.

Try it online: [riosecca.github.io/clipboard-image-viewer](https://riosecca.github.io/clipboard-image-viewer/)

## Usage

1. Open `index.html` in a supported browser.
2. Copy an image.
3. Press `Ctrl + V` (`Cmd + V` on macOS) on the page, or click **Read Clipboard**. You can also open an image by dragging and dropping its file onto the page.

## Features

- Zoom with the mouse wheel or controls
- Fit-to-screen and 100% views
- Drag to pan images
- Horizontal and vertical flipping, plus orientation reset
- Rotate left or right in 90° increments
- Display dimensions, format, file size, and zoom level
- Full-screen view
- Save loaded images as PNG, JPEG, or single-page PDF files
- Movable, collapsible control panel

> Using the Clipboard API may require browser permission and an HTTPS or localhost context. Standard paste operations usually work without additional setup.

## Development

There is no build step or dependency setup. Edit and open `index.html` directly.

## License

This project is licensed under the [MIT License](LICENSE).
