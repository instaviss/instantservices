# Instaviss (single-file)

This archive contains a single-file static site ready to push to GitHub Pages.
It includes:

- `index.html` — your full HTML, CSS and JS in one file (no external assets).

How to publish on GitHub Pages (quick):
1. Create a new repository on GitHub (e.g. `instaviss-formspree`).
2. On your computer extract this ZIP and `cd` into the folder.
3. Initialize git and push to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Instaviss single-file site"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```
4. In the repository on GitHub: Settings → Pages → Source: `main` branch `/ (root)`. Save.
5. Wait a minute — your site will be available at `https://YOUR_USERNAME.github.io/YOUR_REPO/`

Notes:
- Serve over HTTPS/localhost for geolocation to work.
- Formspree action is already configured (`https://formspree.io/f/mrbrbyqd`).
