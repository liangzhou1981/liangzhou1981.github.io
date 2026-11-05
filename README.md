# Liang Zhou — Academic Homepage

Static GitHub Pages site for **[liangzhou1981.github.io](https://liangzhou1981.github.io)**.

## Contents

| Path | Purpose |
|------|---------|
| `index.html` | Single-page academic homepage (English) |
| `styles.css` | Layout and theme (navy / teal) |
| `assets/photo.jpg` | Profile photo (from IEEE author image) |
| `README.md` | This file |

Plain HTML/CSS only (tiny optional JS for mobile nav). No build step.

## Deploy to GitHub Pages

Push the **contents** of this `site/` folder to the root of the repository
[`liangzhou1981/liangzhou1981.github.io`](https://github.com/liangzhou1981/liangzhou1981.github.io)
(or place them under `/docs` and enable Pages from the `docs` folder).

Example (from this directory):

```bash
# After creating the empty liangzhou1981.github.io repo on GitHub:
git init
git add .
git commit -m "Initial academic homepage"
git branch -M main
git remote add origin git@github.com:liangzhou1981/liangzhou1981.github.io.git
git push -u origin main
```

Then enable **Settings → Pages → Deploy from branch → main / (root)**.

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8080
# visit http://localhost:8080
```

## Sources

Facts drawn from IEEE Xplore author profile
[37288728900](https://ieeexplore.ieee.org/author/37288728900)
and the author’s CV (awards, systems, standards, service).
Publication citation counts follow IEEE Xplore metrics in the project brief.
