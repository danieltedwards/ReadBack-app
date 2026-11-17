# Readback

Add a PDF, Word (.docx) or plain-text file, or paste text, and your device reads it out loud.

- Highlights the sentence being spoken; click any sentence to start from there
- Play/pause, previous/next, stop, speed (0.75x to 2x) and voice picker
- Runs entirely in the browser. Files are never uploaded anywhere.
- Uses your device's built-in voices through the Web Speech API, so voice quality depends on your device

## Use it

Open the live page (GitHub Pages) or download `index.html` and open it in a browser. There is no build step.

## Limits

- Scanned PDFs that contain only images of pages have no text to extract (no OCR)
- Old `.doc` files are not supported; save as `.docx` or PDF first

## Built with

[pdf.js](https://mozilla.github.io/pdf.js/) for PDFs, [mammoth.js](https://github.com/mwilliamson/mammoth.js) for .docx, and the browser's `speechSynthesis`.

## License

MIT
