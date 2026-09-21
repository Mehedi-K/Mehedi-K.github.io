# Mehedi-K.github.io

Personal resume/portfolio site, built as a single static page (no build step).

## Publish it on GitHub Pages

1. Create a new **public** repo on GitHub named exactly `Mehedi-K.github.io`
   (must match your username for GitHub to auto-serve it as a user site).
2. From this folder, push it:

   ```bash
   cd mehedi-site
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/Mehedi-K/Mehedi-K.github.io.git
   git push -u origin main
   ```

3. In the repo on GitHub: **Settings → Pages → Source → Deploy from branch →
   `main` / `root`**. Save.
4. Your site will be live at `https://mehedi-k.github.io/` within a minute or two.

## Before you publish — fill these in

- Confirm your name/title in the hero section match what you want shown.
- Swap in real project links under "Projects" if you want to call out
  specific repos instead of the general repositories page.

## Updating later

Edit `index.html` / `style.css`, then:

```bash
git add .
git commit -m "Update site"
git push
```

Changes go live automatically within a minute or two.
