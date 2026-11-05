# DevFolio: Varun Teja Sankineni's Developer Portfolio

A responsive, single-page developer portfolio built with semantic HTML, a small CSS colour and type system, Flexbox and CSS Grid. It adapts from a phone to a desktop screen using mobile-first media queries.

**Live site:** https://varuntejasankineni-coder.github.io/devfolio/

## What's inside

- **Semantic structure:** `<header>` with a `<nav>`, a `<main>` with `#about` and `#projects` sections, and a `<footer id="contact">`
- **Colour + type system:** CSS variables (`--brand`, `--ink`, `--bg`) and one font (Inter)
- **Layout:** Flexbox for the header, nav, skills and contact rows; CSS Grid for the project cards
- **Responsive:** the project grid goes from 1 column on mobile to 2 columns at 600px and 3 columns at 900px, and `img { max-width: 100%; height: auto; }` stops images overflowing
- **Accessibility:** skip link, visible focus styles, comfortable tap targets and reduced-motion support

## Run it locally

No build step is needed.

1. Clone the repo: `git clone https://github.com/varuntejasankineni-coder/devfolio.git`
2. Open `index.html` in your browser (or use the VS Code Live Server extension).

## Project structure

```
devfolio/
├── index.html   # markup
├── style.css    # styles
└── README.md
```

## Deployment

Deployed with GitHub Pages from the `main` branch, root folder (Settings → Pages → Deploy from a branch).
