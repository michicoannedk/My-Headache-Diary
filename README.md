# 🧠 Headache Diary

A personal headache tracking app built for logging chronic headache episodes — as recommended by your doctor.

## What It Tracks

| # | Field | Details |
|---|-------|---------|
| 1 | **Date & Time** | Auto-fills, but fully editable |
| 2 | **Severity** | Slider 1–10 with labels |
| 3 | **Pain Type & Location** | Tap-to-select chips |
| 4 | **Duration** | Hours + minutes |
| 5 | **Other Symptoms** | Nausea, light sensitivity, aura, etc. |
| 6 | **Food & Drink** | Common dietary triggers pre-filled |
| 7 | **Possible Triggers** | Stress, sleep, weather, screens, etc. |
| 8 | **Medication** | What you took & whether it helped |
| 9 | **Notes** | Free text for anything else |

## Features
- 📋 **Home tab** — All episodes in reverse chronological order
- ➕ **Log Episode tab** — Full-featured form with auto time
- 💡 **Doctor Tips tab** — What to track and why
- ✏️ **Edit any log** — Change date/time or any detail later
- 🗑 **Delete logs**
- 📊 **Stats strip** — Total episodes, avg severity, this month
- 🔍 **Filter** — By last 7/30 days or severe (7+) episodes
- 💾 **Local storage** — Your data stays on your device

---

## Deploy to Vercel (Free)

### Step 1 — Push to GitHub
1. Create a new repository on [github.com](https://github.com/new)
2. Name it `headache-diary` (or anything you like)
3. Upload these two files:
   - `index.html`
   - `vercel.json`

   **Option A — via GitHub web interface:**
   - Click **"Add file" → "Upload files"**
   - Drag both files in, click **"Commit changes"**

   **Option B — via terminal:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/YOUR_USERNAME/headache-diary.git
   git push -u origin main
   ```

### Step 2 — Deploy on Vercel
1. Go to [vercel.com](https://vercel.com) and sign up/log in with your GitHub account
2. Click **"Add New Project"**
3. Select your `headache-diary` repository
4. Click **"Deploy"** — no settings needed, `vercel.json` handles it
5. In ~30 seconds you'll get a URL like `headache-diary.vercel.app` 🎉

### Step 3 — Bookmark It
- Open the URL on your phone and **"Add to Home Screen"** for app-like access

---

## Data & Privacy
All your data is saved in your **browser's local storage** — it never leaves your device. No account, no server, no subscription needed.

> ⚠️ If you clear your browser data, your logs will be deleted. Consider taking screenshots before clearing, or export from the app.

---

## For Your Doctor
Use the filter to show recent episodes, then screenshot your log list to share at consultations. The app also has a **Doctor Tips** tab with guidance on what to log.
