# Revision Report

## What was revised

- Rewrote the About section in a more formal academic style.
- Reorganized the navigation into About, Research, Teaching, Education, and Projects & Data.
- Added research fields, working-paper summaries, selected presentations, and selected teaching experience.
- Rewrote the Projects & Data section with clearer academic language.
- Changed the CV link from an absolute URL to a relative link (`CV.pdf`) so it works reliably on GitHub Pages.
- Removed the broken placeholder stylesheet link `path/to/font-awesome/css/font-awesome.min.css`.
- Fixed malformed HTML tags and heading structure.
- Added metadata for search/display and accessibility alt text for the profile image.
- Added a simple `404.html` page and `.nojekyll` file.
- Added a deployment checklist in `README.md`.

## Why the previous site could show "Not Found"

- The uploaded archive contains a nested folder. If that nested folder was committed to GitHub instead of its contents, GitHub Pages would not find `index.html` at the publishing root.
- GitHub Pages for a personal site requires the repository to be named exactly `yuxing-liang.github.io` and to publish from the correct branch/folder.
- The original HTML also requested a nonexistent file: `path/to/font-awesome/css/font-awesome.min.css`. This would not usually break the whole page, but it would create a 404 request in the browser/network log.

## Files changed

- `index.html`
- `README.md`
- `sitemap.xml`
- `404.html`
- `.nojekyll`
- `term-paper.pdf` was added as a space-free duplicate of `term paper.pdf` for safer future linking if needed.
