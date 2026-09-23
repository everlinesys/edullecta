# Edullecta — React/Vite Website

Responsive Edullecta marketing website based on the supplied Student Development Brochure.

## Deploy to Vercel

This project intentionally runs Vite through Node in the npm scripts instead of executing `node_modules/.bin/vite` directly. This avoids Vercel build failures caused by an incorrect executable permission on the Vite shim (`/vercel/path0/node_modules/.bin/vite: Permission denied`).

1. Upload/import this folder as a Vercel project.
2. Framework: Vite (auto-detected).
3. Build command: `npm run build`.
4. Output directory: `dist`.
5. Do not upload `node_modules`.

## Local development

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

The brochure artwork is included at `public/assets/brochure.png`.
