# Portfolio

Personal portfolio site for Miguel Antonio Baliog — plain HTML/CSS/JS, no build step.

## Structure

- `index.html` — all page content and sections (hero, about, experience, projects, skills, contact)
- `css/style.css` — styling (dark theme, single stylesheet)
- `js/main.js` — mobile nav toggle, scroll-reveal animation, footer year
- `assets/` — resume PDF and profile image

## Local preview

Open `index.html` directly in a browser, or serve it:

```bash
npx serve .
```

## Deploying to GitHub Pages

1. Push this repo to `origin` (already set to `github.com/migsszz/Portfolio`).
2. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
3. The site will be published at `https://migsszz.github.io/Portfolio/`.
