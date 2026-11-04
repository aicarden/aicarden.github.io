# Andrés I. Cárdenas — portfolio

Personal academic/industry portfolio. Static HTML/CSS, ready for GitHub Pages.

## Preview locally
Open `index.html` in any browser, or run `python -m http.server 8000` in this folder
and visit http://localhost:8000.

## Publish on GitHub Pages
1. Create a public repo named `YOUR-GITHUB-USERNAME.github.io`.
2. Upload every file in this folder to the repo root (keep the folder structure).
3. In the repo: Settings → Pages → "Deploy from a branch" → `main` / root.
4. The site goes live at `https://YOUR-GITHUB-USERNAME.github.io` within a minute or two.

Note: GitHub Pages file names are case-sensitive (`Projects.html` ≠ `projects.html`).

## Things to fill in
- Site URL in `portfolio.html` (search for `YOUR-GITHUB-USERNAME`).
- GitHub and LinkedIn URLs in the footer of `index.html` (search for `TODO`).
- DOI for the IJHE article in `Publications.html` (search for `TODO`).
- Teaching statement and experience in `Teaching-philosophy.html` (search for `TODO`).
- `files/Andres_Cardenas_CV.pdf`: replace it when your CV changes.

## Pages
- `index.html`: name, about, institutions, recommended pages, contact
- `Research-interests.html`: research statement (foundations → modern tools → multi-agent systems)
- `Work-experience.html`: industrial and academic experience, skills
- `Projects.html`: projects grouped by research line
- `Publications.html`: journal publications, conferences, awards
- `Teaching-philosophy.html`: teaching statement (to be written)
- `portfolio.html`: condensed, print-to-PDF version

## Institution logos
Logos live in `images/institutions/` (`cmu.png`, `scott-institute.png`, `uchile.png`, `energy-center.png`),
cropped to their content so they fill the white banner on each card. Uncropped originals are in
`images/institutions/originals/`. Use lowercase file names without spaces: GitHub Pages is case-sensitive.

Design adapted from astrocassiel.github.io (Gala Cassiel Solis), originally by Nisar (nisar.dev). GPL-3.0, see LICENSE.md.
