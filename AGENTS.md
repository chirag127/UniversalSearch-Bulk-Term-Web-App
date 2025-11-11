# AGENTS.md

## Commands

**Setup:** No setup required - static HTML/CSS/JS site

**Build:** N/A (no build step)

**Lint:** N/A (no linter configured)

**Tests:** N/A (no test framework configured)

**Dev Server:** Open `index.html` in a browser, or use a local server like `python -m http.server` or `npx -y http-server`

## Tech Stack & Architecture

- **Frontend:** Vanilla HTML, CSS, JavaScript (no frameworks)
- **Architecture:** Single-page application with client-side form handling
- **Core functionality:** Multi-search engine query dispatcher that opens search URLs in new tabs

## Code Style

- Standard HTML5 structure with semantic elements
- CSS uses class-based styling with consistent spacing (8px/16px/24px increments)
- JavaScript uses `var` declarations, camelCase naming, and function declarations
- No module system - all code in single files loaded via `<script>` tags
