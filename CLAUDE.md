# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Spendly is a personal finance tracking web application built with Flask. Users can register, log in, add/edit/delete expenses, and view spending patterns by category.

## Commands

```bash
# Run the application
python app.py

# Install dependencies
pip install -r requirements.txt

# Run tests (when implemented)
pytest
```

## Architecture

- **app.py** - Flask application with routes for authentication (login, register, logout) and expense management (add, edit, delete). Currently has placeholder routes for features not yet implemented.
- **database/db.py** - Database layer for SQLite operations. Should implement `get_db()`, `init_db()`, and `seed_db()` functions.
- **templates/** - Jinja2 templates using a base template (`base.html`) with blocks for content. Authentication pages use a consistent card-based layout.
- **static/css/style.css** - CSS with custom properties for theming. Uses DM Serif Display for headings and DM Sans for body text.
- **static/js/main.js** - Client-side JavaScript for interactive features.

## Development Notes

- The app runs on port 5001 in debug mode
- SQLite is the database (connection setup in `database/db.py`)
- Templates extend `base.html` which includes the navbar, main content area, and footer
