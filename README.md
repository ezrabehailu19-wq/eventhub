# EventHub

EventHub is a single-page web app for managing event seats, waitlists, and who gets in. It shows a seat map with different seat states (taken, free, waitlisted) and supports light and dark themes.

## Tech stack

This is a **React project**, delivered as a single HTML file.

- **React 18**, loaded from a CDN (cdnjs), with hooks such as `useState` and `useEffect`
- **JSX**, compiled in the browser by **Babel Standalone** (no build step)
- **CSS**, written in a `<style>` block, using CSS variables and dark mode support
- **Google Fonts**: Bricolage Grotesque and Instrument Sans

The code mentions a Spring Boot API as its intended backend. In this version it runs on **demo data in the browser**, so no server is needed.

## How to run

1. Download or clone this repository.
2. Open `index.html` in a browser (an internet connection is needed to load React, Babel, and the fonts from their CDNs).

## Project structure

```
eventhub/
├── index.html   # the whole app: HTML, CSS, and React code
└── README.md
```

## Notes

Because Babel compiles the JSX in the browser, this setup is great for demos and learning, but a production app would normally use a build tool such as Vite.