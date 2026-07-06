# PT — Portfolio

Personal portfolio website for Parth Tirkar, a full-stack web developer based in Leipzig, Germany.

**Live site:** [https://tirkarparth.github.io/PT/](https://tirkarparth.github.io/PT/)

## Prerequisites

No build tools or package manager is required. You only need:

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- [Git](https://git-scm.com/) (to clone the repository)
- A local web server (recommended — see below)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/TirkarParth/PT.git
cd PT
```

2. That's it — there are no dependencies to install.

## Run Locally

This is a static site (`index.html`, `css/`, `js/`, `img/`). You can open it in two ways:

### Option 1: Local web server (recommended)

Some features work best when the site is served over HTTP rather than opened as a file.

**Python 3** (built in on macOS/Linux):

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

**Node.js** (if installed):

```bash
npx serve .
```

**VS Code / Cursor:** Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension, right-click `index.html`, and choose **Open with Live Server**.

### Option 2: Open directly in the browser

Double-click `index.html`, or drag it into your browser window.

> Note: Opening the file directly (`file://`) may behave slightly differently than the live site (e.g. cookie consent and language settings are stored per origin).

## Project Structure

```
PT/
├── index.html          # Main page
├── css/
│   └── styles.css      # Styles
├── js/
│   ├── cookie-consent.js
│   └── language-toggle.js
├── img/                # Images and icons
└── src/                # Additional assets
```

## Deployment

The site is hosted on **GitHub Pages** from the `main` branch. Pushing changes to `main` automatically updates the live site after GitHub finishes building.

## License

Portfolio page — © Parth Tirkar
