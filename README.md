# Jervin Ancheta — Portfolio

A single-page portfolio site built with plain HTML/CSS/JS (no build step, no dependencies except Google Fonts).

## Deploy on GitHub Pages

1. Create a new repository on GitHub, e.g. `jervin-portfolio`.
2. Upload `index.html` (and this README, optional) to the repo — either by dragging the file into the GitHub web UI ("Add file" → "Upload files"), or via git:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/jervin-portfolio.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch", pick the `main` branch and `/ (root)` folder, then **Save**.
5. Wait a minute, then your site will be live at:
   `https://<your-username>.github.io/jervin-portfolio/`

## Editing later

Everything lives in `index.html` — copy, colors, and layout are all in that one file, so you can hand it to any code editor (or back to Claude) and ask for changes directly.
