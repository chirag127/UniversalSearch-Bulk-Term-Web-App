# AGENTS.md

## Commands

**Initial Setup:** No package installation required. Simply clone the repo and open `index.html` in a browser.

**Build:** N/A (static HTML/CSS/JS)

**Lint:** N/A (no linter configured)

**Tests:** N/A (no test framework configured)

**Dev Server:** Open `index.html` directly in a browser, or use a simple HTTP server like `python -m http.server` or `npx serve .`

## Tech Stack & Architecture

- **Stack:** Pure HTML, CSS, and vanilla JavaScript (no frameworks or dependencies)
- **Architecture:** Single-page application with client-side search URL generation
- **Structure:** Root-level files: `index.html` (UI), `script.js` (search logic), `styles.css` (styling)

## Code Style & Conventions

- Use camelCase for variables and functions (e.g., `searchTerms`, `getSearchUrl`)
- Inline event handlers in HTML (`onclick` attributes)
- No comments unless necessary for complex logic
- Forms use `data-bst` and `data-ast` attributes for search engine URL templates
