# Coding Mikasa

A single-page creative coding reel built with HTML Canvas and the Web Audio API.

## Preview

Open [index.html](./index.html) in a modern browser, or enable GitHub Pages to publish it.

## Project structure

```
.
├── .github/
│   └── workflows/
│       └── pages.yml
├── .gitignore
├── index.html
└── README.md
```

## Run locally

No build step or package manager is required.

1. Clone this repository.
2. Open `index.html` in a modern browser.
3. Interact with the page to enable audio. Browsers require a user gesture before audio playback.

For a local HTTP server, run:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy with GitHub Pages

The included workflow publishes the repository root when changes are pushed to `main`.

In GitHub, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**. Subsequent pushes to `main` will deploy automatically.

## Tech stack

- HTML5
- Canvas 2D API
- CSS
- Web Audio API
- Google Fonts (Anton and JetBrains Mono)

There is no framework, dependency installation, or compilation step.
