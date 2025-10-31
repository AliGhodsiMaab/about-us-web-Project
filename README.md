# Bilito — Simple Airline / About Page

A small, responsive web project that shows an **About Us** page for a Persian (RTL) airline site called **Bilito (بیلیتو)**.  

---

## Overview
This project contains a static HTML page (`index.html`) plus two CSS files.  
The site is primarily right-to-left (Persian) and includes a header, an about section, footer, and small interactive behaviors implemented with plain JavaScript.

---

## Key features
- Clean, responsive layout for desktop and mobile.
- Right-to-left (RTL) support for Persian content.
- Header with logo, mobile hamburger menu and navigation links.
- "About us" tabbed area with goals and services text.
- Footer with contact details, app store badges and social icons.
- Small interactive scripts:
  - Mobile menu open/close.
  - Smooth "back to top" button.
  - Simple login prompt that saves the visitor name to `localStorage`.
  - Alert for unavailable travel insurance link.

---

## Files included
- `index.html` — Main page (Persian content, RTL).
- `css.css` — Primary site styles (layout, responsive rules, RTL).
- `style.css` — Additional / alternate styling (fonts, dark background, demo counters).
- `img/` — Images used by the page (logo, icons, badges, background, etc.).
- `fonts/` — Local font files referenced by `style.css` (optional).

---

## How to use
1. Clone the repository.
2. Make sure the `img/` and `fonts/` folders are present beside `index.html`.
3. Open `index.html` in a browser to view the page locally.
4. (Optional) Deploy on GitHub Pages or any static hosting provider by publishing the repository.

---

## Notes & suggestions
- The page content is in Persian (UTF-8). To convert to English, replace the Persian texts in `index.html`.
- `css.css` controls the RTL layout and responsive behavior. `style.css` contains an alternate theme and UI components — merge or keep separate depending on your site structure.
- Accessibility improvements: add `aria-*` attributes, semantic landmarks, and `alt` text for all images.
- If you plan to publish, update contact info and remove demo `alert()` / `prompt()` scripts or replace with real authentication flows.

---

## Quick file map
