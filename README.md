# Atari Source Render
Single page tool to render an ATASCII source files (with 0x9B line endings) to a PNG image, optionally rounding up to 80, 120, or 256 chars. 

This is useful for visualizing minified FastBasic source files.

This runs locally in the browser using javascript, using the canvas element.

**atascii.png** is not used direcly, but is the source for the base64 encoded charset in index.html, and included here in case someone finds it useful.