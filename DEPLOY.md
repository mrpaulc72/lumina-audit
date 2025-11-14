# 🚀 Deploy to GitHub Pages

Follow these steps to get your lead magnet live at: **https://mrpaulc72.github.io/lumina-audit/**

---

## Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. **Repository name**: `lumina-audit`
3. **Description**: "Free Forensic Property Audit lead magnet for Lumina Property Management"
4. **Visibility**: Public (required for GitHub Pages)
5. **Do NOT** initialize with README, .gitignore, or license
6. Click **"Create repository"**

---

## Step 2: Push Your Code

Run these commands in Terminal:

```bash
cd /Users/paul/dev/lumina-audit
git branch -M main
git remote add origin https://github.com/mrpaulc72/lumina-audit.git
git push -u origin main
```

---

## Step 3: Enable GitHub Pages

1. Go to your repository: https://github.com/mrpaulc72/lumina-audit
2. Click **Settings** (top menu)
3. Click **Pages** (left sidebar)
4. Under "Source":
   - Branch: **main**
   - Folder: **/ (root)**
5. Click **Save**

---

## Step 4: Wait (2-3 minutes)

GitHub will build and deploy your site. You'll see:
- "Your site is ready to be published at..."
- Then: "Your site is live at https://mrpaulc72.github.io/lumina-audit/"

---

## ✅ Done!

Your lead magnet is now live at:

**https://mrpaulc72.github.io/lumina-audit/**

---

## 🔄 Future Updates

Whenever you make changes:

```bash
cd /Users/paul/dev/lumina-audit
git add .
git commit -m "Description of changes"
git push
```

Wait 1-2 minutes for GitHub Pages to rebuild.

---

## 📱 Share Your Link

**Short URL**: https://mrpaulc72.github.io/lumina-audit/

**Use in**:
- Email signatures
- Social media posts
- LinkedIn articles
- Facebook/Instagram ads
- Website popups
- Print materials (as QR code)

---

## 🎯 Track Performance

Add Google Analytics to track:
- Page views
- CTA clicks
- Form submissions
- Calendly bookings

---

## 🆘 Troubleshooting

**"404 Not Found"**
- Wait 2-3 minutes after enabling Pages
- Check Settings → Pages shows "Your site is live"
- Refresh with Cmd/Shift + R (hard refresh)

**"Images not showing"**
- Check images are in `assets/images/` folder
- Verify paths in HTML use `assets/images/` (not `../assets/images/`)

**"Form not submitting"**
- Open browser console (F12)
- Check for JavaScript errors
- Verify Calendly URL is correct

---

**Questions?** Everything is ready to deploy. Just follow the steps above!

