# jbpt.de — Personal Profile Page

Personal brand website for Jacob Bo Lueg Tiedemann, Product Leader & Technologist. Hosted on GitHub Pages at [jbpt.de](https://jbpt.de).

## Overview

A single-page profile site built to promote my personal brand, showcase my portfolio, and serve as a central hub to connect with me online. Designed with a minimal, modern aesthetic optimised for readability and performance.

## Structure

```
├── index.html          # Main single-page application
├── imprint.html        # Impressum (legal notice, German law)
├── privacy.html        # Datenschutzerklärung (GDPR privacy policy)
├── css/
│   ├── style.css       # Main stylesheet & design tokens
│   └── legal.css       # Styles for legal pages
├── js/
│   └── main.js         # Navigation, scroll behaviour, animations
└── img/                # Profile photo, favicon assets
```

## Sections

- **Hero** — Name, role, tagline, and profile photo
- **About** — Biography, career journey, skills & expertise tags
- **Portfolio** — Case study cards: OTA Platform Scale, IoT Product Launch, Organisational Transformation
- **Speaking & Writing** — Topics and formats for speaking engagements
- **Contact** — Links to LinkedIn, Speakerdeck, and email

## Tech Stack

- Plain HTML5, CSS3, and vanilla JavaScript — no frameworks, no build tools
- Fonts: [Inter](https://fonts.google.com/specimen/Inter) (body) + [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) (display) via Google Fonts
- Animations via Intersection Observer API
- Hosted on **GitHub Pages** with a custom domain (`jbpt.de`)

## Design Tokens

The visual design is defined through CSS custom properties in `css/style.css`:

| Token | Value | Usage |
|---|---|---|
| `--color-primary` | `#2D6A6A` | Accent, CTAs, links |
| `--color-bg` | `#F7F4EF` | Page background |
| `--color-surface` | `#EDE8DF` | Section backgrounds |
| `--color-text` | `#1C1C1E` | Primary text |
| `--font-display` | Space Grotesk | Headings |
| `--font-body` | Inter | Body copy |

## Features

- Responsive design (mobile-first, breakpoints at 480px / 768px / 1024px)
- WCAG-compliant accessibility (skip link, ARIA labels, focus styles, reduced motion support)
- SEO optimised (meta tags, Open Graph, Twitter Card, JSON-LD structured data)
- Cross-browser compatible
- No JavaScript dependencies

## Deployment

The site is deployed automatically via GitHub Pages from the `main` branch. The custom domain is configured via the `CNAME` file.

## Legal

- Impressum: `/imprint.html`
- Datenschutzerklärung: `/privacy.html`
- © Jacob Bo Lueg Tiedemann
