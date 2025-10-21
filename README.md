# 5‑Tab To‑Do (No-build, PWA-ready)

A pure HTML/CSS/JS to‑do app with 5 tabs and overdue logic. Ready to deploy on **GitHub Pages** and install on iPhone/Android as a PWA.

## Features
- Tabs: Home, Overdue, Urgent (5 days), Semi‑urgent (10 days), Sometime (30 days)
- Add tasks, choose insert Top/End, re‑order ↑/↓, move between categories
- Auto‑Overdue once past due date
- Saves to localStorage; includes offline cache (service worker)

## Deploy (GitHub Pages)
1. Create a repo (e.g. `five-tab-todo`).
2. Upload these files to the **root** of the repo:
   - `index.html`
   - `manifest.webmanifest`
   - `service-worker.js`
   - `icons/icon-192.png`
   - `icons/icon-512.png`
3. Commit to `main`.
4. Settings → Pages → Source: **Deploy from a branch**, Branch: `main`, Folder: **/ (root)**.
5. Visit `https://<your-username>.github.io/<repo>/`

## Install on iPhone
Open the site in Safari → Share → **Add to Home Screen**. Works offline and persists on the device.
