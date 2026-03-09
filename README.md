<<<<<<< HEAD

<h1 align="center">
AcadHomepage
- `index.html` — homepage
- `research.html` — research overview
- `publications.html` — publications
- `talks.html` — talks
- `cv.html` — CV page
- `assets/css/style.css` — styling
- `.github/workflows/pages.yml` — GitHub Pages deployment workflow

## Quick deployment to GitHub Pages

1. Create a repository named `haozheliu.github.io` on GitHub.
2. Upload all files from this folder to the repository root.
3. Commit to the `main` branch.
4. In GitHub: `Settings` → `Pages`.
5. Under **Build and deployment**, choose **GitHub Actions**.
6. Push once more if needed. The workflow in `.github/workflows/pages.yml` will publish the site.

## What to edit first

### 1. Homepage identity
Edit in `index.html`:
- email
- Google Scholar / GitHub / LinkedIn links
- title / affiliation
- selected publication titles

### 2. Publications
Edit `publications.html`:
- venue names
- final author lists
- paper/code/project links
- BibTeX links

### 3. CV
Replace the placeholder file with your own PDF:
- path: `static/files/Haozhe_Liu_CV.pdf`

## Suggested next refinements

- Add a profile photo only if you really want one; the current design intentionally avoids it.
- Keep the homepage short.
- Put papers first.
- Use few colors.
- Avoid project cards and heavy animations.
