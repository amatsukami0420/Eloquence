# Eloquence

Eloquence is a multi-page, front-end chess training dashboard focused on repertoire building, study workflows, and analysis UI. The project is built with HTML, CSS, Bootstrap, and a small amount of JavaScript for interactive components.

## Project Overview

The interface provides a complete navigation flow across:

1. Dashboard landing experience with carousel and module cards
2. Repertoire management table
3. Study room with an interactive chessboard
4. PGN analysis input view
5. Contact page with support form
6. User profile view with progress indicators
7. Authentication screen with Sign In and Register tabs

This is currently a static front-end implementation intended for UI/UX and structure demonstration.

## Tech Stack

1. HTML5
2. CSS3
3. Bootstrap 5.3.2 (CDN)
4. Bootstrap Icons 1.11.1 (CDN)
5. Google Fonts: Montserrat
6. jQuery 3.7.1 (used in Study Room)
7. Chessboard.js 1.0.0 (used in Study Room)

## Pages and Features

### Dashboard

File: index.html

1. Sticky top navigation bar
2. Hero carousel with rotating slides
3. Quick-access cards for core modules
4. Unified footer branding

### Repertoire

File: repertoire.html

1. Search input for variations
2. Repertoire table with opening status and win-rate placeholders
3. Pagination UI

### Study Room

File: study.html

1. Interactive chessboard (drag-and-drop pieces)
2. Reset and clear board controls
3. Accordion-based opening variation notes
4. Key concept checklist with badges

### Analysis

File: analysis.html

1. PGN paste area
2. Analysis action buttons (Run/Clear)
3. Informational alert for engine workflow

### Contact

File: contact.html

1. Support details section
2. Contact form with name, email, and message fields

### Profile

File: profile.html

1. Profile summary card
2. Rating display
3. Skill progress bars for training categories

### Authentication

File: login.html

1. Tabbed Sign In and Register interface
2. Sign In form (email + password)
3. Register form (name, email, password, confirm password)
4. Action buttons route to the dashboard entry page

## Shared UI Patterns

1. Consistent sticky navbar across pages
2. Shared footer styling and text
3. Global Montserrat typography via style.css
4. Flex-based page shell for stable footer placement

## Folder Structure

```text
Eloquence/
|-- index.html
|-- repertoire.html
|-- study.html
|-- analysis.html
|-- contact.html
|-- profile.html
|-- login.html
|-- style.css
|-- images/
|   |-- engine.jfif
|   |-- master.jfif
|   |-- monitor.jfif
|-- README.md
```

## Run Locally

No build step is required.

1. Clone or download the repository
2. Open the project folder in VS Code
3. Open index.html directly in a browser, or use Live Server for auto-refresh

## Notes

1. This project currently has no backend or persistent storage
2. Form actions and analysis actions are UI-level placeholders
3. Navigation and layout are optimized around a static prototype workflow

## Author

Muhammad Waleed Bin Anwar
FA24-BCS-110
