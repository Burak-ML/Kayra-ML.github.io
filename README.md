# Portfolio website

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222?logo=githubpages)

**A single-page personal portfolio built with plain HTML, CSS and JavaScript, bundled with Vite and published on GitHub Pages.**

The page has a hero section with a typing animation, a grid of featured projects that link to their repositories, and a footer with contact links.

## Development

```bash
npm install
npm run dev        # local dev server
npm run build      # production build into dist/
npm run preview    # preview the production build
```

## Deployment

Pushing to `main` runs `.github/workflows/deploy.yml`, which installs dependencies, builds the site and publishes `dist/` to GitHub Pages. In the repository settings, set **Pages → Source** to **GitHub Actions**.

A user site is only served at `https://<username>.github.io` when the repository is named exactly `<username>.github.io`.

## Project structure

```
index.html     page markup and project cards
style.css      styles
main.js        typing animation
public/        static assets
```

## License

MIT. See [LICENSE](LICENSE).
