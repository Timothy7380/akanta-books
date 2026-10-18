# Akanta Books

Accounting workspace built for Geoinfotech Holdings (Nigeria).

**Live app:** served by GitHub Pages from `index.html`.

## What it does
- Upload bank statements (PDF, including password-protected, Excel or CSV); lines are auto-categorised by bank rules and matched to invoices
- Overview: income vs expenses (daily / weekly / monthly / yearly), highest expense, top income source, profit or loss
- Cost reduction plan: next month's budget = last month's spend minus a target %
- Reports: executive summary, income statement, statement of financial position, cash flow, notes to the accounts — download as PDF or Excel
- Invoices with multiple business profiles, logos, 7.5% VAT and WHT — download as PDF
- Payroll with PAYE (Nigeria Tax Act 2025 bands), pension, payslips
- Tax centre: reminders for VAT, WHT, PAYE, pension, CIT and development levy (NRS / Rev360, State IRS)
- Double-entry ledger, chart of accounts, journals, trial balance, fixed assets & depreciation, period lock, audit trail

## Notes
- Data is stored in the browser (localStorage) on each device. Nothing is sent to a server.
- The app opens with clearly labelled example figures; use **Start with real books** to clear them.
- Tax rates and deadlines are editable under Settings → Tax & deadlines. Confirm them with NRS / your State IRS.
