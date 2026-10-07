[![CI](https://github.com/the-jodingo/car-webapp.html/actions/workflows/ci.yml/badge.svg)](https://github.com/the-jodingo/car-webapp.html/actions/workflows/ci.yml)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
# Odingo — Car Showroom Landing Page

A single-page landing site for a fictional Italian performance-car marque, featuring the Odingo 296 GTB. Plain HTML, CSS, and vanilla JavaScript.

## Table of contents

- [Requirements](#requirements)
- [Usage](#usage)
- [Deployment](#deployment)
- [Accessibility](#accessibility)
- [License](#license)

## Requirements

A modern web browser. No build step, no dependencies, no server required.

## Usage

```bash
git clone https://github.com/the-jodingo/car-webapp.html.git
cd car-webapp.html
python3 -m http.server 8000
```

Open <http://localhost:8000>. You can also open `index.html` directly.

## Deployment

Any static host works — Netlify, GitHub Pages, Cloudflare Pages, S3, or nginx.
The page is a single file with no build step, so you can drag the folder in.

## Accessibility

- semantic landmarks and a logical heading order
- all text meets WCAG AA contrast
- keyboard-navigable, with visible focus states
- responsive layout, usable from 320 px wide
- CI runs an axe-core scan and HTML validation on every push

## License

[MIT](LICENSE) © Joash Odingo
