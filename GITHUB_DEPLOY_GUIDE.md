# 🌐 GitHub Pages Deployment Guide
## د AMS ERP سیستم آنلاین کولو لارښود
### How to Put Your ERP Online — Accessible on Any Phone or Computer

---

## ✅ What You Need
- A **GitHub account** (free) — sign up at [github.com](https://github.com)
- The 3 files: `index.html`, `sw.js`, `manifest.json`

---

## 📋 Step-by-Step (10 minutes)

### Step 1 — Create a GitHub Account
1. Go to **https://github.com**
2. Click **Sign Up**
3. Enter email, password, username
4. Verify your email

---

### Step 2 — Create a New Repository
1. Click the **+** button (top right) → **New repository**
2. Repository name: `ams-erp` (or any name)
3. Set to **Public** ✅
4. Click **Create repository**

---

### Step 3 — Upload Your Files
1. On your new repository page, click **uploading an existing file**
2. **Drag and drop** all 3 files:
   - `index.html`
   - `sw.js`
   - `manifest.json`
3. Scroll down → Click **Commit changes**

---

### Step 4 — Enable GitHub Pages
1. Click **Settings** tab (in your repository)
2. Scroll down to **Pages** section (left sidebar)
3. Under **Source** → Select **Deploy from a branch**
4. Branch: **main** → Folder: **/ (root)**
5. Click **Save**

---

### Step 5 — Get Your URL
After 1-2 minutes, your URL will be:

```
https://YOUR-USERNAME.github.io/ams-erp/
```

Example: `https://aryanmarketing.github.io/ams-erp/`

**Share this URL with your team — it works on any device!**

---

## 📱 How to Install as App on Phone

### Android (Chrome):
1. Open the URL in Chrome
2. Tap the **3 dots menu** (⋮)
3. Tap **"Add to Home Screen"**
4. Tap **Install**
5. App icon appears on your home screen!

### iPhone (Safari):
1. Open the URL in Safari
2. Tap the **Share button** (□↑)
3. Scroll down → Tap **"Add to Home Screen"**
4. Tap **Add**

### Computer (Chrome/Edge):
1. Open the URL
2. Click the **install icon** (⊕) in the address bar
3. Click **Install**
4. Opens like a real desktop app!

---

## 🔒 Important Notes About Data

| Topic | Info |
|-------|------|
| **Data Storage** | Each device stores its own data (IndexedDB) |
| **Sharing Data** | Use **Export Backup** button to share data between devices |
| **Import Data** | Coming in next version |
| **Internet** | Only needed first time. After that, works offline! |
| **Cost** | GitHub Pages is completely **FREE** |

---

## 🔄 How to Update the System

If you get a new version of `index.html`:
1. Go to your GitHub repository
2. Click on `index.html`
3. Click the **pencil icon** (Edit)
4. Or drag and drop the new file to replace it
5. Click **Commit changes**
6. Wait 1-2 minutes → refresh your URL

---

## 👥 Team Access

Give your team the URL. Each person:
- Uses their own login (admin or staff)
- Has their own local database
- Can export/import to sync data

For **shared database** (future): A backend server (Node.js + MongoDB) would be needed — ask your developer.

---

## 🆘 Troubleshooting

| Problem | Solution |
|---------|----------|
| Page not loading | Wait 5 minutes after enabling Pages |
| Old version showing | Press **Ctrl+Shift+R** (hard refresh) |
| Login not working | Try admin / admin123 |
| Data disappeared | Data is per-browser. Use Export Backup! |

---

## 📞 Your System URL

After setup, write your URL here:

**URL:** `https://________________.github.io/ams-erp/`

---

*Aryan Marketing Services — AMS ERP v2.0*  
*ماركبتينگ خدمات — د سوداګرۍ مدیریت سیستم*
