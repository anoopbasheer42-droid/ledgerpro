# LedgerPro

A free, offline-first accounting software for small businesses in India.

Built with HTML, CSS, and JavaScript. Uses IndexedDB for local storage.
No backend, no API keys, no monthly costs.

---

## Current Status

**Stage 1 — Single-user, offline accounting**
- Free forever
- Runs entirely in the browser
- Data stored locally in IndexedDB
- Backup via JSON export/import

**Stage 2 — Multi-user SaaS (future)**
- Will require a backend
- Same frontend will be reused
- Only attempted after Stage 1 is stable and validated

---

## Scope — Stage 1 MVP

The first working version will include 8 core modules:

| # | Module | Purpose |
|---|--------|---------|
| 1 | Login / Company Setup | Guided onboarding |
| 2 | Dashboard | 6 financial cards + charts + quick actions |
| 3 | Chart of Accounts | The accounting foundation |
| 4 | Customers | Customer list, balances, statements |
| 5 | Items | Products and services |
| 6 | Invoices + Payments | Invoicing with payment tracking |
| 7 | Expenses + Suppliers | Expense tracking + supplier bills |
| 8 | Reports | P&L, Balance Sheet, Trial Balance |

Advanced modules (inventory, banking, GST returns, multi-currency, AI assistant) will be added after Stage 1 is validated.

---

## Design Principles

1. **Plain language first.** "Money customers owe you" instead of "Accounts Receivable".
2. **Clickable numbers.** Every figure on the dashboard opens its underlying records.
3. **Double-entry always.** Every posted transaction balances debits and credits.
4. **No silent edits.** Posted transactions are corrected via reversal, not overwrite.
5. **Offline first.** Works without internet.
6. **Mobile friendly.** Designed for Xiaomi Pad 8 and phone screens.

---

## Currency and Tax

- Currency: **INR (₹)**
- Tax: **GST** (CGST, SGST, IGST) — configured in settings
- Financial Year: **April 1 – March 31** (India)

---

## Technology Stack — Stage 1

| Component | Technology |
|-----------|-----------|
| Structure | HTML5 |
| Styling | CSS3 (light theme) |
| Logic | Vanilla JavaScript (ES6+) |
| Storage | IndexedDB |
| Charts | Chart.js (via CDN) |
| PDF export | Browser print-to-PDF |
| Hosting | GitHub Pages (dev only) |
| Source | GitHub |

No frameworks. No build tools. No dependencies to install.

---

## File Structure
