# Ainin Najihah — e-Portfolio (A211021)

A single-page e-Portfolio for my Mobile App Development coursework, built around
**Jobsy** (SDG 1: No Poverty). Plain HTML/CSS/JS — no build step needed.

## Files
- `index.html` — the portfolio page
- `styles.css` — styling
- `script.js` — mobile menu + screenshot lightbox
- `assets/` — app logo and lab/project screenshots

## Preview locally
Just open `index.html` in a browser, or run a tiny server:

```bash
cd eportfolio
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy to GitHub Pages
1. Create a new GitHub repo (e.g. `eportfolio`).
2. Put the **contents of this `eportfolio` folder** at the root of the repo
   (so `index.html` is at the repo root), then push:
   ```bash
   git init
   git add .
   git commit -m "Add e-portfolio"
   git branch -M main
   git remote add origin https://github.com/aininnajihah/eportfolio.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Build and deployment**.
   - Source: **Deploy from a branch**
   - Branch: **main** / **/(root)** → Save.
4. Wait ~1 minute. Your site will be live at:
   `https://aininnajihah.github.io/eportfolio/`

## Notes / things to update
- The GitHub repo buttons point to:
  - Project 1: `https://github.com/aininnajihah/A211021_Aininnajihah_MrNelson_Project1`
  - Project 2: `https://github.com/aininnajihah/A211021_Aininnajihah_MrNelson_Project2`
  Update these in `index.html` if your repo names differ.
- The **Project 1 / Project 2 screenshot folders were empty**, so I temporarily
  reused relevant lab screenshots. Drop your real project screenshots into
  `assets/lab4` (Project 1) / `assets/lab5` (Project 2) — or new folders — and
  update the `<img>` paths in the Projects section.
