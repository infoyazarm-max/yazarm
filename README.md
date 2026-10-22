# Yazarm website — standalone React + Vite

A standalone React rebuild of the Yazarm marketing homepage. It includes responsive navigation, hero, services, destination gallery, reasons to choose Yazarm, testimonials, about, contact and footer sections.

## Run locally

```bash
npm install
npm run dev
```

Production build: `npm run build`. For Vercel, use the Vite preset, build command `npm run build`, and output directory `dist`.

## Deploy to Vercel

1. Import this repository into Vercel.
2. Confirm the Vite preset, `npm run build`, and `dist`.
3. Deploy and compare the preview with the existing Base44 site before changing domains.

## Important asset note

The website currently references the original public Base44 image URLs for photography and background textures. The app no longer uses Base44 runtime components or backend services, but to remove the last hosting dependency, copy those image files into `public/images/` and update the URLs in `src/App.jsx` and `src/index.css`.

Please confirm the testimonial wording and permission to publish before going live.
