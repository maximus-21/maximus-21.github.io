# Dhruv Portfolio (Eleventy + Tufte CSS)

This website uses:

- [Tufte CSS](https://edwardtufte.github.io/tufte-css/)
- Eleventy static site generator
- An Eleventufte-inspired structure

## Local development

```bash
npm install
npm start
```

Open `http://localhost:8080`.

## Build

```bash
npm run build
```

Build output is generated in `_site/`.

## Content files

- `src/index.njk`
- `src/projects.md`
- `src/publications.md`

The homepage (`src/index.njk`) includes the About section.

Shared layout and data:

- `src/_layouts/frontpage.njk`
- `src/_layouts/page.njk`
- `src/_includes/head.njk`
- `src/_includes/footer.njk`
- `src/_data/site.json`
- `src/_data/navigation.json`
- `src/assets/css/tufte-custom.css`

## Deployment

Deployment is handled by GitHub Actions:

- Workflow: `.github/workflows/deploy-eleventy.yml`
- Trigger: push to `main`
- Output: GitHub Pages

## Design inspiration

- [Tufte CSS](https://edwardtufte.github.io/tufte-css/)
- [Eleventufte](https://github.com/nerdhaus/eleventufte/tree/main)
- [Tyler Romero's website and repo](https://www.tylerromero.com/) · [GitHub](https://github.com/tyler-romero/tyler-romero.github.io)
