# AGENTS.md - English Materials

## Project Overview
Static HTML site for English learning materials (quizzes, tests, grammar tasks, flashcards) for B1–C2 learners.

## Project Structure
- `index.html` - Main entry page with navigation
- `*.html` - Individual quiz/exercise pages (B1-C2 level English exercises)
- `*.html` files are self-contained with embedded CSS/JS
- No build system, no package.json, no build tools - pure static HTML

## Development
- Open `index.html` directly in browser to view
- No build step, no server required
- Edit HTML files directly to add/edit content

## Conventions
- Each HTML file is self-contained (embedded CSS/JS)
- CSS uses CSS custom properties (variables) for theming
- Vanilla JavaScript (ES6 modules not used)
- CEFR levels indicated in filenames (A2, B1, B2, C1, C2)

## Development Notes
- No build tools, no package.json, no tests
- Static files only - deploy by copying to any static host
- No linting, formatting, or type checking configured
- Use GitHub MCP tools for GitHub operations (push, PRs, issues) instead of git CLI