# 🚀 GitHub Profile Portfolio — Complete Setup Guide

---

## 📦 Folder Structure

```
Datamancer42/                      ← Upload THIS entire folder as your repo
├── README.md                      ← Your profile page (auto-renders on GitHub)
├── SETUP.md                       ← This guide
└── .github/
    └── workflows/
        └── snake.yml              ← Auto-generates the contribution snake animation
```

---

## ⚡ Step 1 — Create Your Profile Repository

1. Go to **https://github.com/new**
2. Repository name: **`Datamancer42`** ← must match your GitHub username exactly
3. Set to **Public**
4. ✅ Do **NOT** tick "Initialize with README"
5. Click **Create repository**

---

## 📤 Step 2 — Upload Files

### Option A — GitHub Web UI (easiest)
1. After creating the repo, click **"uploading an existing file"**
2. Drag and drop **all files and folders** keeping the folder structure intact:
   - `README.md`
   - `SETUP.md`
   - `.github/workflows/snake.yml`
3. Commit to `main`

### Option B — Git CLI
```bash
cd Datamancer42          # this folder
git init
git remote add origin https://github.com/Datamancer42/Datamancer42.git
git add .
git commit -m "🚀 Initial portfolio setup"
git branch -M main
git push -u origin main
```

---

## 🐍 Step 3 — Enable Contribution Snake (2 minutes)

The snake animation uses GitHub Actions. After pushing files:

1. Go to your repo → **Settings** → **Actions** → **General**
2. Under *Workflow permissions* → select **"Read and write permissions"** → Save
3. Go to **Actions** tab → click **"Generate Contribution Snake"** → **"Run workflow"**
4. Wait ~1 minute — the snake SVGs are generated in an `output` branch
5. ✅ Snake now appears in your README automatically!

> The workflow also runs automatically every 12 hours to keep the snake updated.

---

## 🖼️ Dynamic Widgets — All Auto-Update

Every image in the README is a live CDN widget. No setup needed — they pull your real GitHub data automatically.

| Widget | Service | Updates |
|---|---|---|
| Header / Footer Banner | `capsule-render.vercel.app` | Static (always renders) |
| Typing Animation | `readme-typing-svg.herokuapp.com` | Static (always renders) |
| GitHub Stats Card | `github-readme-stats.vercel.app` | Every few hours |
| Top Languages | `github-readme-stats.vercel.app` | Every few hours |
| Streak Stats | `streak-stats.demolab.com` | Daily |
| Activity Graph | `github-readme-activity-graph.vercel.app` | Daily |
| Trophy Shelf | `github-profile-trophy.vercel.app` | Daily |
| Profile Views | `komarev.com/ghpvc` | Real-time |
| Repo Pin Cards | `github-readme-stats.vercel.app` | Every few hours |
| Contribution Snake | GitHub Actions → `output` branch | Every 12 hours |

---

## ✏️ Customisation Tips

### 🎨 Change banner color gradient
In `README.md`, find `customColorList=0,2,2,5,30` and try:
- `0,2,2,5,30` → Blue/Purple (current — cool tech vibe)
- `6,11,20` → Deep navy
- `12,20,27` → Green neon
- `24,25,26` → Red/orange fire

### ⌨️ Change typing lines
Find `&lines=` in the typing SVG URLs. Each line is separated by `;`. Use `+` for spaces and `%7C` for `|`.

### 🔗 Update your LinkedIn & Email
Search for `Datamancer42` and `your.email@example.com` in `README.md` and replace with your actual URLs.

### 🃏 Repo pin cards auto-populate
The pinned repo cards use `github-readme-stats` and pull live data — no manual update needed as long as the repo names match exactly.

---

## ✅ Checklist

- [ ] Created repo named exactly `Datamancer42`
- [ ] Uploaded `README.md`, `SETUP.md`, and `.github/workflows/snake.yml`
- [ ] Enabled "Read and write permissions" in Actions → Settings → General
- [ ] Ran the **"Generate Contribution Snake"** workflow manually once
- [ ] Updated LinkedIn URL and Email in `README.md`
- [ ] Visited `github.com/Datamancer42` to confirm it looks great! 🚀
