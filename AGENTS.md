# AGENTS.md - MultiSearchX Development Guide

## Commands

**Initial Setup:** None required (vanilla HTML/CSS/JS)

**Build:** N/A (no build step)

**Lint:** N/A (no linter configured)

**Tests:** N/A (no test suite)

**Dev Server:** Open `index.html` in a browser, or use any static server (e.g., `python -m http.server` or VS Code Live Server)

## Tech Stack

- Pure HTML5, CSS3, and vanilla JavaScript
- No frameworks or build tools
- Client-side only application

## Architecture

- `index.html`: Main UI with form controls and search engine checkboxes
- `script.js`: Search logic, URL generation, and tab opening functionality
- `styles.css`: Styling for form elements and layout

## Code Style & Conventions

- Use camelCase for variables and functions (e.g., `searchTerms`, `getSearchUrl`)
- Inline event handlers in HTML (`onclick` attributes)
- No comments unless necessary for complex logic
- Forms use `data-bst` and `data-ast` attributes for search engine URL templates
