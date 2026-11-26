# Robel's Class Website

A personal gallery and portfolio site built for a class assignment on
**accessibility and inclusive design**. Dark mode only, keyboard‑navigable,
and screen‑reader friendly — from the first pixel to the last interaction.

> 🌐 Live site: *(add your GitHub Pages URL here once published)*  
> 🐙 Source: https://github.com/ROBELG1999/class-website

---

## ✨ Features

- **Dark‑mode‑only design** — a deliberate choice, tuned for readability and low eye strain.
- **Accessible by default** — semantic HTML, landmarks, `aria-*` attributes, and visible focus rings on every interactive element.
- **Keyboard‑first interactions** — everything works with <kbd>Tab</kbd>, <kbd>Enter</kbd>, <kbd>Space</kbd>, and <kbd>Esc</kbd>. No mouse required.
- **Responsive mobile nav** — a hamburger toggle that expands/collapses the menu without a page reload.
- **Accessible contact form** — inline, screen‑reader‑announced error messages (no `alert()` popups), live character counter, and automatic focus on the first invalid field.
- **Live GitHub card** — powered by the public GitHub REST API via `fetch()`, with graceful error handling and a fallback link.
- **Reduced‑motion support** — respects `prefers-reduced-motion` for users who need it.

---

## 🛠️ Tech Stack

| Layer | Tool |
|---|---|
| Markup | HTML5 (semantic, ARIA where needed) |
| Styling | Plain CSS (custom properties, `clamp()`, grid, `prefers-reduced-motion`) |
| Behaviour | Vanilla JavaScript (no frameworks, no build step) |
| Data | [GitHub REST API](https://docs.github.com/en/rest) — free, no key required |

No bundlers, no dependencies. Open the file and it runs.

---

## 📁 File Structure

