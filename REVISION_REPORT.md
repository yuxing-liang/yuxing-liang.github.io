# Revision Report

## Requested update

The user requested cosmetic and content revisions to the job-market website: replace the sharp-looking font, keep the main color unchanged, remove "education markets" keyword language, restore supervisor names and links, and add presentation slides for SSCW 2026 Tokyo to the job-market paper section.

## Changes made

1. **Typography and visual polish**
   - Replaced the previous Source Sans / Source Serif pairing with a softer academic pairing: Nunito Sans for body text and Literata for headings.
   - Preserved the main burgundy color: `#912338`.
   - Softened card shadows, rounded buttons/cards, and improved spacing.

2. **Job-market content**
   - Kept the job-market banner visible near the top.
   - Rewrote the job-market abstract to emphasize the distinction between strategy-proofness, deviations from truth, decision relevance, and allocatively costless deviations.
   - Added a direct "Request Draft" email button.

3. **Supervisor links**
   - Restored supervisors in the About section:
     - Prof. Szilvia Pápai
     - Prof. Xintong Han

4. **Slides**
   - Added the uploaded SSCW 2026 slides to `assets/docs/sscw-2026-liang-slides.pdf`.
   - Linked the slides from the Job Market Paper card and Selected Presentations section.

5. **Keyword cleanup**
   - Removed the phrase "education markets" from the field/keyword language.
   - Replaced it with more precise language: school choice, college admissions, major assignment, assignment mechanisms, and applied microeconomics.

## Deployment note

Upload the contents of the package to the root of the GitHub Pages repository. If the site appears unstyled, the CSS folder is not at the root or the old `index.html` is still being served.


## v3 update: Analytical Workbench

- Added a new sidebar section, **Workbench**, with the title **Analytical Workbench**.
- Added brief language on data processing, coding, econometric/statistical workflows, simulations, and visual reporting.
- Added a concise description of the independent financial-market analytics project, framed as analytical infrastructure rather than investment advice.
- Added selected visual examples from the uploaded market-analysis visual files: IV surface, GEX/moneyness heatmap, wall/level structure, and intraday tape.
- Kept the existing main color `#912338` unchanged.

## v4 update: positioning, advising hierarchy, and lighter workbench

- Replaced the equal supervisor-card presentation with a more accurate and diplomatic advising sentence: Yuxing is advised by Prof. Szilvia Pápai, and his research has also benefited from external supervision and guidance from Prof. Xintong Han.
- Rewrote the homepage profile to position Yuxing as a matching theory / market design researcher whose work is theory-first but connected to empirical and computational methods.
- Kept the dark Analytical Workbench design, but made the section cleaner and less heavy by shortening the text, removing the extra three-card explanation block, and reducing the visual mosaic to three compact examples.
- Changed the Workbench nav label to “Methods” while keeping the page title “Analytical Workbench.”
- Simplified the Background section to emphasize only the Ph.D. candidate status at Concordia University, with the full education history left to the CV.
- Added a subtle line about research-oriented opportunities using economic modeling, empirical analysis, and computational methods, without changing the main academic/postdoctoral job-market emphasis.
