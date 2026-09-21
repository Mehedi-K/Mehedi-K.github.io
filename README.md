# Mehedi-K.github.io

Personal resume/portfolio site for Mehedi K. — Full-Stack Engineer, Senior Solutions Architect & QA Automation Engineer. A single static page, no build step, no framework, served directly by GitHub Pages.

**Live:** [mehedi-k.github.io](https://mehedi-k.github.io/)

## Structure

```
index.html   All page content and markup
style.css    Styling — CSS custom properties for theme colors, layout, and animation
```

The page is a single-scroll "pipeline" layout: hero header, then five stages (Background, Stack, Experience, Projects, Contact), styled with a terminal/build-pipeline motif (`$ whoami`, stage indices, amber/teal accent colors).

## Updating

Edit `index.html` / `style.css` directly, then:

```bash
git add .
git commit -m "Update site"
git push
```

Changes go live via GitHub Pages within a minute or two — no separate deploy step, no CI.

## Deployment

Served from the `main` branch root via GitHub Pages (Settings → Pages → Deploy from branch → `main` / `root`). The repo name matching the GitHub username (`Mehedi-K.github.io`) is what makes GitHub auto-serve it as a user site at the root domain.
