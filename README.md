# Responsive Blog Cards (Tailwind CSS)

![Vite](https://img.shields.io/badge/Vite-latest-646CFF?logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-CDN-38B2AC?logo=tailwind-css&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

Responsive blog card layout built with vanilla HTML and Tailwind CSS. The project focuses on clean UI design, accessible content (line clamps, focus states), and recruiter-friendly code structure. Every card includes hover states, author avatars, interaction icons, and a newsletter footer for user engagement.

![Responsive blog cards preview](img/logo.png)

## Table of Contents
- [Overview](#overview)
- [Live Demo](#live-demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Overview
This repository delivers a polished front-end layout for a plant-themed blog. It demonstrates how to compose responsive cards using Tailwind’s utility-first approach without a build step—perfect for showcasing UI skills or bootstrapping a content-driven landing page.

## Live Demo
- [Responsive Blog Cards](https://bakadja.github.io/responsive-blog-cards-tailwind/)

## Features
- Responsive grid that adapts from stacked cards on mobile to multi-column layouts on larger screens.
- Tailwind CDN setup for instant styling without a local build pipeline.
- Accessible typography and layout choices, including semantic HTML, focus-visible states, and clamped text to avoid overflow.
- Hover effects on images, cards, and icons to reinforce interactivity.
- Newsletter subscription footer to highlight conversion opportunities.

## Installation
```bash
git clone https://github.com/bakadja/responsive-blog-cards-tailwind.git
cd responsive-blog-cards-tailwind
npm install
```
> Requires Node.js 18+ to match Vite’s current baseline.

## Usage
Start a local dev server with hot reload:
```bash
npm run dev
```

Build the production bundle (outputs to `dist/`):
```bash
npm run build
```

Preview the production build locally:
```bash
npm run preview
```

Open `index.html` directly in a browser if you prefer a zero-build workflow; the page pulls Tailwind from the official CDN.

## Configuration
- **Card content**: Update titles, authors, and copy inside `index.html` to swap in your own stories.
- **Media assets**: Replace the files in `img/` with your imagery (keep filenames or update `src` references).
- **Branding**: Customize header navigation links, the SVG logo, and the footer newsletter copy to suit your brand.
- **Tailwind styles**: Add custom utility classes inline or introduce a `tailwind.config.js` plus a local build step if you want to extend Tailwind beyond the CDN defaults.
- **Analytics or embeds**: Insert additional scripts (e.g., for analytics) in the `<head>` while keeping performance in mind.

## Contributing
1. Fork the repository and create a new branch for your feature or fix.
2. Run `npm run dev` while editing to verify layout changes across viewport sizes.
3. Add or update documentation and screenshots when UI components change.
4. Open a pull request describing the update and the testing performed.

## License
Distributed under the [MIT License](LICENSE).

## Acknowledgments
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first styling approach.
- [Vite](https://vitejs.dev/) for the fast development workflow.
- Plant-inspired copywriting that brings character to each card.
