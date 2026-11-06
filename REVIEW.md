# Workbook review

Reviewed the supplied Dashboard.xlsx without editing or resaving it.

## Checks passed
- 300 data records and 300 unique order IDs.
- All 300 sales values match Units × Unit Price × (1 − Discount), within 0.01.
- Total sales: 22,664,039.86; total cost: 16,530,848.00; calculated profit: 6,133,191.86.
- Monthly sales and regional sales/profit agree with the source records.
- Category sales totals agree with the source records.
- The five products displayed are the five highest-selling products (the workbook lists them alphabetically).
- The profit calculated field uses Sales − Cost.
- Four charts, two slicers and the About Project statements are present.
- No saved Excel error cells were found.

## Details to be aware of
1. Pivot!A20 reads “Top 5 products by sales” above the regional table. This is a label mismatch.
2. The Salesperson and Segment slicers connect to the four chart PivotTables, but not PivotTable8, which holds total sales. The card displays a fixed overall total of 22.66 M; no cell-link formula was found in the shape. Treat it as overall sales, not filtered sales.
3. The dashboard title remains “TRAINING DASHBOARD”. This is cosmetic.

The workbook was inspected structurally and numerically. Native Excel rendering, slicer clicks and refresh behavior have not been tested in Microsoft Excel; this is not a guarantee that every visual or interaction is perfect.

## File integrity
Original and downloadable workbook bytes match exactly.
SHA-256: 659a8fa17d8f6ef0f6f2f15c567e27e8a6a99cdd405d262a38f6b878c3b07ea2
