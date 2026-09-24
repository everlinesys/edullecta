# Edullecta React Website

React + Vite website for Edullecta — Education, Skills & Opportunities.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Notes

- The Edullecta logo is cropped directly from the supplied brochure artwork and used as the site logo.
- The brochure image has been removed from the hero section.
- The hero now uses a new Kerala/student image asset at `public/assets/hero-students.jpg`.
- AOS (Animate On Scroll) is loaded from the official unpkg CDN and initialized from React.
- The project intentionally runs Vite through Node (`node node_modules/vite/bin/vite.js`) to avoid Vercel executable-permission issues with `node_modules/.bin/vite`.
