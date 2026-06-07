# Push to GitHub — Quick Start (2 minutes)

## Option 1: Using GitHub Web UI (Easiest — 30 seconds)

1. **Go to** https://github.com/new
2. **Create repository:**
   - Name: `bombay-bioenergy-tracker`
   - Description: `Live project file tracker for Bombay Bioenergy`
   - Public (so it's accessible)
   - Click "Create repository"

3. **Upload files:**
   - Click "Add files" → "Upload files"
   - Drag these 3 files:
     - `bombay-bioenergy-file-tracker.html`
     - `BOMBAY_BIOENERGY_TRACKER_README.md`
     - `bombay-bioenergy-tracker-manifest.json` (optional)

4. **Click "Commit changes"**

**Done!** Your tracker is live at: `https://github.com/YOUR_USERNAME/bombay-bioenergy-tracker`

---

## Option 2: Using Git Command Line (Advanced)

If you already have Git installed:

```bash
# 1. Create folder
mkdir bombay-bioenergy-tracker
cd bombay-bioenergy-tracker

# 2. Initialize Git
git init
git add .
git commit -m "Initial commit: Bombay Bioenergy project file tracker"

# 3. Add remote (replace USERNAME)
git remote add origin https://github.com/YOUR_USERNAME/bombay-bioenergy-tracker.git

# 4. Push
git branch -M main
git push -u origin main
```

---

## What to Upload

Three files needed:
1. **bombay-bioenergy-file-tracker.html** (main tracker)
2. **BOMBAY_BIOENERGY_TRACKER_README.md** (documentation)
3. **bombay-bioenergy-tracker-manifest.json** (optional — data source)

All files are in: `/mnt/user-data/outputs/`

---

## After Upload

**Your tracker will be live at:**
```
https://github.com/YOUR_USERNAME/bombay-bioenergy-tracker
```

**To use it:**
- Click the HTML file on GitHub
- Click "Raw" to open it
- Or download the HTML file and open locally in any browser

---

## Adding Future Files

Edit the HTML file directly on GitHub:
1. Click the `.html` file
2. Click the pencil icon (Edit)
3. Find `const allFiles = [`
4. Add new entry
5. Commit

---

That's it! ✨
