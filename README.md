# Alireza Mirrokni — Lumina Academic Homepage

This is a customized version of the Lumina academic website template for Alireza Mirrokni.

## Local preview

```bash
npm install
npm run dev
```

Open the localhost link printed by Astro.

## Build

```bash
npm run build
```

The static site is created in `dist/`.

## Main editing files

- `site.config.yml`: name, links, theme, enabled pages, avatar path
- `src/content/about.md`: homepage biography and research interests
- `src/content/publications/papers.bib`: publications
- `src/content/teaching/courses.yml`: teaching and TA experience
- `src/content/cv/cv.yml`: CV, education, experience, skills, service
- `public/images/avatar.svg`: replace with your real photo and update `site.config.yml`
- `public/images/publications/`: paper teaser images
- `public/images/projects/`: research-area/project images

## Deploy to GitHub Pages

Create a GitHub repository named `alirezamirrokni.github.io`, push this project to the `main` branch, then enable GitHub Pages with Source = GitHub Actions.
