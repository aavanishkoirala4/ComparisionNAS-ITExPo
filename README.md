# NAS-IT Expo 2026: Exhibitor Landscape

A static website summarising the exhibitors at NAS-IT Expo 2026 (Heritage Garden, Kathmandu): what each company sells, how they compare, what they have in common, market gaps and business opportunities.

## Structure

```
index.html     page content
css/style.css  styles (light and dark mode, responsive, print)
.nojekyll      tells GitHub Pages to serve files as they are
```

No build step and no JavaScript. Fonts load from Google Fonts with system fallbacks.

## Run locally

Open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000.

## Deploy on GitHub Pages

1. Create a new public repository, for example `nas-it-expo-2026`.
2. Upload all files in this folder to the repository root, or push them:
   ```
   git init
   git add .
   git commit -m "Add NAS-IT Expo 2026 site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/nas-it-expo-2026.git
   git push -u origin main
   ```
3. In the repository go to Settings, then Pages. Under Build and deployment choose Deploy from a branch, pick `main` and `/ (root)`, and save.
4. After a minute the site is live at `https://<your-username>.github.io/nas-it-expo-2026/`.
