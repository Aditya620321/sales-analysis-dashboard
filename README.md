# Excel Sales Analysis Dashboard

An Excel portfolio project by Aditya Shashank, with a responsive HTML and CSS showcase page.

## Files
- `index.html`: project overview and static charts based on the workbook data.
- `styles.css`: responsive styling; no JavaScript or external dependencies.
- `Dashboard.xlsx`: the original, unchanged Excel workbook.
- `REVIEW.md`: numerical checks and remaining workbook caveats.

## View locally
Extract this folder and open `index.html`. Keep `styles.css` and `Dashboard.xlsx` beside it. The download button opens or downloads the workbook, depending on your browser settings.

## Publish on GitHub Pages
1. Create a public repository named `sales-analysis-dashboard`.
2. Upload the **contents of this folder**, including the Excel file, to the repository root. Do not upload only the ZIP.
3. Commit the uploaded files.
4. Open Settings → Pages → Build and deployment.
5. Select Deploy from a branch, then `main` and `/ (root)`, and Save.
6. After deployment, copy the URL displayed on the Pages settings page.

## Scope
The webpage is a static summary, not an embedded Excel application. Open the downloaded workbook in desktop Excel to use its PivotCharts and slicers. Website values do not change when the workbook is edited. Currency is not specified in the source, so values are displayed without a currency symbol.

## Dataset summary
300 orders; 2,024 units; total sales 22,664,039.86; total cost 16,530,848.00; total profit 6,133,191.86. The source is the supplied project workbook; no real-company or independent provenance claim is made.
