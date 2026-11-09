# Stockroom Ledger

A lightweight inventory demo for a small import and wholesale business (hair care and beauty products), built as a single HTML page with no server.

**Live demo:** _add your GitHub Pages link here_

## What it shows

- **Stock in / stock out that always reconcile.** Balances are calculated from every posted movement, not typed in by hand.
- **Pick verification.** A shipment can only be posted when the picked count matches the customer PO.
- **Customer tracking.** Every shipment is tied to a retailer, with order history per customer.
- **Bilingual label queue.** Imported stock is held until Canadian English/French stickers are printed, applied and scan-checked.
- **Stock counts.** Differences are posted as adjustments with a reason, so the ledger is never edited.
- **Reports.** Pie charts for stock in, stock out, sales by customer and warehouse capacity, plus a daily in/out bar chart.
- **Three languages.** English, Simplified Chinese and Traditional Chinese.

## Notes

- All data is **sample data**. Company and contact details are placeholders.
- Entries are saved in the viewer's own browser (localStorage). Use **Reset sample data** at the bottom of the page to start over.
- Label requirements are based on general Health Canada guidance and are not legal or regulatory advice.
