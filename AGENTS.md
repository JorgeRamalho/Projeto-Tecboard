# Tecboard

Static landing page for a real-time application monitoring product (Brazilian Portuguese).

## Cursor Cloud specific instructions

### Project structure

Pure static HTML/CSS site with no dependencies, build tools, or package managers:
- `index.html` — single-page landing
- `css/style.css` — responsive styles (desktop, tablet at 768px, mobile at 375px)
- `fonts/` — custom TTF fonts (Unbounded Bold, Poppins Regular)
- `img/` — logos and mockup images

### Development server

Serve locally with Python's built-in HTTP server:

```
python3 -m http.server 8080
```

Then open http://localhost:8080/ in a browser.

### Lint / Test / Build

- **Lint**: No linter configured. Optionally use an HTML validator or stylelint.
- **Tests**: No automated tests exist.
- **Build**: No build step — the site is served directly from source files.

### Notes

- There is no `package.json`, `Makefile`, or any dependency file.
- The update script is intentionally a no-op (`true`) since there are no dependencies to install.
- To test responsive CSS, use Chrome DevTools device mode at 768px (tablet) and 375px (mobile) breakpoints.
