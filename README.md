# Dhruv Portfolio (Jekyll)

A simple Jekyll portfolio site for GitHub Pages.

## Quick start (local)

1. Install Ruby + Bundler
2. Run:

```bash
bundle install
bundle exec jekyll serve
```

3. Open `http://127.0.0.1:4000`

## Customize

- Edit profile info in `_config.yml`
- Edit homepage in `index.md`
- Edit `about.md`, `projects.md`, `publications.md`
- Update navigation in `_data/navigation.yml`

## Deploy to GitHub Pages

### Option A: User site (recommended)

- Create repo named `yourusername.github.io`
- Push this project to that repo root
- Visit `https://yourusername.github.io`

### Option B: Project site

- Use any repo name (e.g., `portfolio`)
- In `_config.yml`, set:
  - `url: "https://yourusername.github.io"`
  - `baseurl: "/portfolio"`
- Enable GitHub Pages in repo Settings
