# Records of Repair — Gosford Library

A single-page site: material passports for the former Gosford Library. There is nothing to build. `index.html` is the whole site.

## Put it online with GitHub Pages

1. Create a new repository on GitHub (public, unless your plan allows private Pages).
2. Upload everything in this folder to the repository root: `index.html`, `404.html`, `.nojekyll`, `README.md`. Drag and drop in the web page works.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose your main branch and the **/ (root)** folder, then save.
5. Wait a minute or two. The site appears at `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

## Notes

- `.nojekyll` stops GitHub from processing the files, so the site is served exactly as written.
- All links are relative, so it works at a repository sub-path as well as on a custom domain.
- The fonts load from Google Fonts, so a first visit needs an internet connection. If offline, the site falls back to system fonts.
- Changes made in the browser (new approaches, logged records, uploaded images) last for the visit only and reset on reload.

## Updating

Replace `index.html` in the repository and commit. Pages redeploys on its own.
