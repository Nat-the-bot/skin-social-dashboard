# Skin Social Financials

This folder contains all financial records for Skin Social, organized by month.

## Structure

Each subfolder is named `YYYY-MM-monthname` and contains:
- `financials.md` — Full data in readable markdown tables (every sheet, every number)
- `financials.json` — Full data in JSON format (machine-readable, all sheets)
- `[month]-[year]-original.xlsx` — Original QuickBooks export file

## Months Available

| Month | Folder | Sheets |
|---|---|---|
| January 2026 | `2026-01-january/` | Balance Sheet, Balance Sheet Detail, Balance Sheet by Month, P&L, P&L Detail, P&L 12 Month Trailing |
| March 2026 | `2026-03-march/` | Balance Sheet, Balance Sheet Detail, Balance Sheet by Month, P&L, P&L Detail, P&L 12 Month Trailing |

## Quick Summary

| Month | Revenue | Net Income |
|---|---|---|
| January 2026 | $76,714 | -$15,512 (inflated COGS due to $19K early vendor prepayments) |
| March 2026 | $107,671 | +$29,139 |

*Add new months by dropping the xlsx into this repo and running the extraction script.*
