# Lab 2: Visual Detective — Frequency Distributions & Graphs

This is a student-only, static GitHub Pages package. It requires no server, database, account, or external library.

## Publish with GitHub Pages

1. Create a new public GitHub repository (for example, `visual-detective`).
2. Upload `index.html`, `style.css`, and `app.js` to the root of the repository.
3. Commit the files.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/(root)`, then save.
7. After GitHub finishes publishing, open the displayed Pages URL.

## Test before assigning

1. Enter a Case Code already tested in Lab 1. Confirm the verification code and all 30 rows match Lab 1 exactly.
2. Refresh and enter the code again. Confirm the dataset is unchanged.
3. Test a categorical frequency table and a grouped quantitative table.
4. Generate all four graph types and download at least one graph image.
5. Confirm the histogram table appears below histogram and frequency-polygon graphs.
6. Check the assignment sidebar on both desktop and a narrow/mobile browser window.

## Compatibility

The dataset generator in `app.js` deliberately preserves Lab 1's exact `DD1|` seed namespace, FNV-1a hash, Mulberry32-style random number generator, generation order, planted patterns, unusual observation, dataset schema, and verification-code formula. The same Case Code therefore recreates the same employee data.

## Files

- `index.html` — student page and finalized assignment questions
- `style.css` — responsive layout and visual design
- `app.js` — seeded dataset, tables, charts, and downloads

No instructor page is included. Case Codes are processed locally in the browser and are not stored or transmitted by this package.
