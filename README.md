# Smart Medical Store Management System — Professional Version 2

A more professional local pharmacy-management application built with Flask, SQLite, HTML5, CSS3 and vanilla JavaScript.

## Included
- Professional dashboard with KPI cards and sales/profit/stock visualizations
- Secure session login with role-based Admin/Staff permissions
- Medicine master + batch management
- FEFO batch selection (earliest expiry first)
- Purchase/inward stock with existing-batch support
- POS sales with validation against expired/out-of-stock quantities
- Printable professional invoices
- Customers and suppliers with history summaries
- Stock adjustments for damaged/returned/expired stock
- Expiry 30/60/90-day views
- Sales, purchase, profit, stock valuation and expiry reports
- CSV report export
- Global search
- Low-stock, expiry and payment alerts
- Settings for shop details used on invoices
- SQLite database; easy to migrate to MySQL later
- Optional Java stock-calculation utility

## Demo Login
Admin: `admin` / `admin123`
Staff: `staff` / `staff123`

## Windows setup
```bat
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python database/init_db.py
python backend/app.py
```
Open: http://127.0.0.1:5000

## Notes
This is a local/demo business application, not a certified pharmacy/medical billing product. Before real deployment, add organization-specific tax, invoice, accounting, backup, audit and regulatory requirements.
