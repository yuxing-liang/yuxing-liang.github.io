# Yuxing Liang Academic Website

This is a static GitHub Pages website for Yuxing Liang.

## What changed in this version

- Added a visible 2026–2027 academic job market banner.
- Added a dedicated Job Market Paper section with a polished abstract.
- Added job-market fields, research interests, and postdoctoral-position language.
- Reorganized the page into About, Job Market, Research, Teaching, Education, and Contact.
- Updated typography using Source Sans 3 and Source Serif 4.
- Preserved the original main burgundy color `#912338`.
- Added a separate custom stylesheet: `css/site-polish.css`.
- Kept `index.html` at the repository root for GitHub Pages deployment.

## Deployment instructions

Upload the CONTENTS of this folder to the root of the GitHub repository named:

```text
yuxing-liang.github.io
```

The repository root should contain:

```text
index.html
404.html
CV.pdf
.nojekyll
assets/
css/
js/
```

Do not upload the whole folder as a nested directory. GitHub Pages must be able to see `index.html` at the root.

Then check:

```text
Settings → Pages → Deploy from a branch → main → / root
```

## Important notes

- The Job Market Paper PDF is not linked because the current package does not include a final JMP PDF. The page says “Draft available upon request.”
- Replace `CV.pdf` with your newest CV before uploading if you have an updated version.
- If you later add a PDF for the Job Market Paper, place it in the root folder or a `papers/` folder and update the link in `index.html`.
