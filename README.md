# A Letter From My Heart

A romantic interactive letter and birthday surprise built with React, TypeScript, Vite, Tailwind CSS, Framer Motion and Lucide icons.

## Live Website

https://azhardayo.github.io/website-1-love-letter/

## Run Locally

```sh
npm ci
npm run dev
```

To use a specific port:

```sh
npm run dev -- --port 5173
```

## Build

```sh
npm run build
npm run preview
```

The production files are generated in `dist/`.

## Personalize

Edit `src/data/content.ts` to change the letter text, poetry, love notes, birthday wishes and other messages. Optional music can be added under `public/assets/` and configured in the same content file.

## Deployment

This repository publishes the built `dist/` output through the `gh-pages` branch and GitHub Pages.