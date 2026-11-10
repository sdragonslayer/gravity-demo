# CLAUDE.md

## Project

Gravity Sandbox: a three.js N-body gravity simulator. The whole app lives in a single file, `index.html` (HTML, CSS, and an ES module script).

## Conventions

- Keep it a single self-contained `index.html`, with no build step and no bundler.
- three.js comes from jsDelivr through the import map, pinned to `three@0.170.0`. Keep the version pinned.
- Run it with any static server (`npx serve .` or `python -m http.server`). Opening the file directly won't work because of the ES module imports.
- Keyboard shortcuts are defined in the `keydown` handler. Update the README's controls table when you change them.
