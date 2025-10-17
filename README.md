# Sales Summary 374959384

Single-page website that reads data.csv from the repository, sums the `sales` column, and displays the total.

Features
- Uses Bootstrap 5 from jsDelivr CDN for styling.
- Parses CSV (simple parser sufficient for provided data).
- Sets document title to "Sales Summary 374959384".
- Displays total inside the #total-sales element.

Deployment
- The site is ready to be deployed on GitHub Pages. Push the repository to GitHub and enable Pages from the repository settings (serve from the main branch root).

Files
- index.html — the entire single-page app.
- data.csv — CSV file (already present in repository).
- githhub_sample.jpeg — sample image (already present in repository).

Notes
- The CSV parser is simple and assumes no embedded commas inside quoted fields (suitable for the provided CSV).
- If you update data.csv, refresh the page to see the updated total.

Commit
- See commit_message file for the commit note.