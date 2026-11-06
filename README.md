# Excel Sales Analysis Dashboard

I built this Excel dashboard to analyze sales trends, compare sales and profit across categories and regions, and identify the top five products by sales.

I also created a responsive HTML and CSS webpage to showcase the project and provide the original Excel workbook for download.

## View the Project

- [Open the Website](./index.html)
- [Download the Excel Workbook](./Dashboard.xlsx)

To view the live website, use the GitHub Pages link in this repository’s About section. The website link above opens the HTML source when viewed on GitHub.

## Project Objective

My goal was to turn sales records into a clear dashboard that helps answer questions such as:

- Which month generated the highest sales?
- Which categories contributed the most sales and profit?
- How did sales and profit vary across regions?
- Which five products generated the most sales?
- How did performance differ by segment and salesperson?

## Tools and Skills Used

- **Microsoft Excel:** PivotTables, PivotCharts, calculated fields, slicers and dashboard formatting
- **HTML:** Webpage structure and workbook download links
- **CSS:** Page styling, static charts and responsive layouts
- **GitHub Pages:** Website hosting

## Dataset Overview

The workbook contains 300 sales records with the following fields:

| Type | Fields |
| --- | --- |
| Identifiers and dimensions | Order ID, Order Date, Region, Category, Product, Segment, Salesperson |
| Numeric fields | Units, Unit Price, Discount, Sales, Cost |
| Calculated measure | Profit = Sales − Cost |

## What I Built in Excel

1. Created PivotTables to summarize monthly, category, regional and product performance.
2. Created a line chart to show monthly sales trends.
3. Calculated profit using Sales minus Cost.
4. Created a combo chart to compare sales and profit across categories.
5. Created a clustered column chart to compare sales and profit across regions.
6. Created a bar chart showing the top five products by sales.
7. Added a total-sales KPI card.
8. Added Segment and Salesperson slicers to filter the four charts.
9. Combined these elements into a single dashboard.

## Key Results

| Metric | Value |
| --- | ---: |
| Total orders | 300 |
| Total units sold | 2,024 |
| Total sales | 22,664,039.86 |
| Total cost | 16,530,848.00 |
| Total profit | 6,133,191.86 |

### Insights

- **July** recorded the highest monthly sales, at approximately **3.40 million**.
- **Electronics** contributed approximately **75.2%** of total sales.
- **South** generated the highest regional sales, at approximately **6.45 million**.
- **Printer** was the leading product by sales value, at approximately **5.44 million**.

## Project Files

| File | Purpose |
| --- | --- |
| `index.html` | Project showcase page with a static summary of the workbook data |
| `styles.css` | Styling and responsive layouts |
| `Dashboard.xlsx` | Original Excel project with data, PivotTables, charts and slicers |
| `README.md` | Project overview and usage instructions |

## Workbook Sheets

| Sheet | Contents |
| --- | --- |
| Data | Source sales records |
| Pivot | PivotTables supporting the dashboard |
| Dashboard | Charts, total-sales card and slicers |
| About Project | Summary of the work completed |

## How to Explore the Project

### Excel Workbook

1. Download `Dashboard.xlsx`.
2. Open it in Microsoft Excel on your computer.
3. Select the **Dashboard** sheet.
4. Use the **Segment** and **Salesperson** slicers to explore the charts.
5. Clear the slicer selections to return to the full dataset.

The total-sales card displays the overall dataset total and does not change with the slicer selections.

### Website

The webpage presents a static overview of the project, including key figures, charts and a workbook download button.

To view it locally, download the repository, keep `index.html`, `styles.css` and `Dashboard.xlsx` in the same folder, and open `index.html` in a browser.

## Scope and Limitations

- This is a learning and portfolio project based on the supplied sales dataset.
- The webpage uses HTML and CSS; it does not run Excel PivotTables or slicers in the browser.
- Website figures are static and do not automatically update when the workbook changes.
- The Excel download preserves the original workbook rather than converting it into a webpage.
- Values marked **M** on the webpage are expressed in millions.

## What I Learned

Through this project, I practiced summarizing data with PivotTables, calculating profit, selecting suitable charts and using slicers to explore results.

I also learned how to present an Excel project through a simple webpage so visitors can understand the analysis and download the workbook.
