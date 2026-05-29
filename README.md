# OT Tracker — Workforce Hours & Overtime

A self-hosted overtime tracking app for facilities management. Runs on GitHub Pages — free, no server required, works on any device including mobile.

---

## 🚀 Setup: GitHub Pages (5 minutes)

### Step 1 — Create a GitHub account
Go to https://github.com and sign up (free).

### Step 2 — Create a new repository
1. Click the **+** icon top right → **New repository**
2. Name it: `ot-tracker`
3. Set to **Public**
4. Click **Create repository**

### Step 3 — Upload the file
1. On your new repo page, click **Add file** → **Upload files**
2. Drag and drop `index.html` from this folder
3. Scroll down, click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Click **Settings** (top of repo)
2. Left sidebar → **Pages**
3. Under "Branch" select **main** and folder **/ (root)**
4. Click **Save**

### Step 5 — Access your app
After ~60 seconds your app is live at:
```
https://YOUR-USERNAME.github.io/ot-tracker
```
Bookmark this on your phone. Works on Android, iPhone, desktop — any browser.

---

## 🔑 API Key Setup (for AI image reading)

1. Go to https://console.anthropic.com
2. Sign in → **API Keys** → **Create Key**
3. Copy the key (starts with `sk-ant-api03-...`)
4. In the OT Tracker app, paste it in the API key field and click **SAVE KEY**

Your key is stored only in your browser's local storage — never sent anywhere except Anthropic's API directly.

---

## 📱 Add to Home Screen (Mobile)

**Android Chrome:**
1. Open your GitHub Pages URL
2. Tap the 3-dot menu → **Add to Home screen**
3. Tap **Add**

**iPhone Safari:**
1. Open your GitHub Pages URL
2. Tap the Share icon → **Add to Home Screen**
3. Tap **Add**

---

## Features
- 📸 AI image reader — upload calendar photos, AI extracts worker/hours/location data
- ✏️ Manual entry with autocomplete
- ⚡ OT Summary — weekend & holiday overtime grouped by day
- 📅 Regular Days — weekday hours log
- 📊 Totals — per-worker and per-location breakdowns
- 📋 Justify Report — auto-generated management justification narratives
- ⬇ CSV and PDF export
- 💾 Data saved in browser localStorage — persists between sessions
