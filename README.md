[README.md](https://github.com/user-attachments/files/25737895/README.md)
# Azure AppGW ICM CRI Analysis Dashboard

Interactive dashboard analyzing 30 ICMs across Azure Application Gateway with root cause trends, PM recommendations, and Engineering action items.

## 🚀 Deploy to GitHub Pages (5 minutes)

### Step 1 — Create a new GitHub repo
1. Go to [github.com/new](https://github.com/new)
2. Name it: `appgw-icm-dashboard` (or anything you like)
3. Set visibility: **Public** (required for free GitHub Pages)
4. Click **Create repository**

### Step 2 — Upload the file
1. In your new repo, click **Add file → Upload files**
2. Drag and drop `index.html` from this folder
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to your repo **Settings** → scroll to **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Branch: `main` · Folder: `/ (root)`
4. Click **Save**

### Step 4 — Get your public URL
- After ~60 seconds, your dashboard will be live at:
  ```
  https://<your-github-username>.github.io/appgw-icm-dashboard/
  ```
- GitHub will show the URL in Settings → Pages once deployed

## 📋 Dashboard Features
- **Overview & Trends** — Root cause bar chart, deflectable pie chart, key patterns
- **ICM Explorer** — All 30 ICMs, filterable by cause category, expandable with full detail + DRI owner
- **PM Actions** — 6 prioritized recommendations (P0–P2) with insight + action
- **Eng Actions** — 7 engineering priorities with pattern observed + engineering action

## 🔧 No build step required
This is a single `index.html` file with React and Recharts loaded from CDN. Just upload and share.
