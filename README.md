# Aryan Marketing Services — ERP System
## Deployment & Usage Guide

---

## What's Included

| File | Purpose |
|------|---------|
| `index.html` | Complete ERP application (single file) |
| `manifest.json` | PWA manifest (installable app) |
| `sw.js` | Service Worker (offline support) |

---

## Quick Start (Local Use)

1. **Double-click `index.html`** — works immediately in any modern browser
2. Login with: **admin / admin123** (full access) or **staff / staff123**
3. All data saves automatically to your browser's IndexedDB (permanent, no internet needed)

---

## Hosting (Recommended for team use)

### Option A — Free Hosting with Netlify
1. Go to [netlify.com](https://netlify.com) → Drag the entire folder to deploy
2. Share the URL with your team
3. Each device has its own local database

### Option B — Local Web Server
```bash
# Python
python -m http.server 8080

# Node.js
npx serve .
```
Open `http://localhost:8080`

---

## PWA Installation (Works Like a Desktop App)

1. Open in Chrome or Edge
2. Click the install icon (⊕) in the address bar
3. Click "Install" — it appears on your desktop/taskbar
4. Runs fully offline, no browser UI

---

## Features

### 🔐 Login System
- Admin and Staff roles
- Remember me (stays logged in)
- Demo credentials shown on login page
- Add more users in Settings

### 📊 Dashboard
- Live metrics: active contracts, expiring soon, monthly income/expenses, net profit, pending payments
- Alert panel for overdue and near-due payments
- Monthly bar chart (income vs expenses)

### 📁 Contracts
- Auto-generated contract IDs
- Service types: Facebook Management, Graphic Design, Video Editing, Photography, Sponsorship, Printing, Content Writing, Ads Management, Community Management
- Auto-calculated: Next Due Date, Days Remaining
- Status badges: Active (green), Pending (amber), Expired (gray)
- Color-coded urgency: overdue (red), near expiry (amber)
- One-click PDF contract generation with signature/stamp area

### 🧾 Invoices
- Auto invoice numbering: AMS-001, AMS-002...
- Multi-line item table with qty × price
- Paid amount tracking and balance calculation
- PDF export with company branding, signature, stamp area
- "Not valid without signature and stamp" notice

### 💰 Income
- Manual income entry or auto-created from invoices
- Filter by month, year
- Monthly and yearly totals

### 💸 Expenses
- Categories: Salary, Rent, Ads, Transport, Tools, Utilities, Other
- Filter by category
- Monthly and yearly totals
- Auto-deducted from profit calculations

### 📄 Reports
- All-time income, expenses, net profit
- Top 5 clients by revenue (with progress bars)
- Expense breakdown by category
- Export to PDF

### ⚙️ Settings
- Company name, phone, email, address (used in all PDFs)
- User management (add/remove users)
- Export all data as JSON backup
- Clear all data

---

## Data Storage

- **Primary**: IndexedDB (browser built-in, survives restarts, no size limit for typical use)
- **Session**: localStorage (remember-me feature)
- **No server required** — 100% offline capable

---

## Supported Currencies

All amounts are in **AFN (Afghan Afghani)** by default. To change the currency label, find `AFN` in `index.html` and replace with your currency code.

---

## Browser Support

| Browser | Support |
|---------|---------|
| Chrome 80+ | ✅ Full (recommended) |
| Edge 80+ | ✅ Full |
| Firefox 75+ | ✅ Full |
| Safari 14+ | ✅ Full |

---

## Security Note

This system uses browser storage. For sensitive business data:
- Use on a trusted device
- Set a strong browser password
- Use the "Export Data" backup regularly
- Consider hosting on a private server for team use

---

*Built for Aryan Marketing Services — AMS ERP v1.0*
