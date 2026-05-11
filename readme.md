# Quantara — Deployment Guide

## Your site files

```
quantara/
├── index.html        ← Homepage
├── students.html     ← Student card rankings
├── compare.html      ← Card comparison tool
├── article.html      ← Blog article layout
└── css/
    └── styles.css    ← Shared styles
```

---

## Option A: Deploy with Netlify (recommended — free, takes 2 minutes)

1. Go to https://netlify.com and sign up for a free account
2. From your dashboard click **"Add new site" → "Deploy manually"**
3. Drag and drop the entire `quantara` folder onto the upload area
4. Netlify gives you a live URL instantly (e.g. `quantara-abc123.netlify.app`)
5. Optional: go to **Site settings → Domain management** to set a custom domain

To update your site later: drag and drop the folder again — Netlify replaces the old version.

---

## Option B: Deploy with GitHub Pages (free, best for version control)

### Step 1 — Create a GitHub account
Go to https://github.com and sign up.

### Step 2 — Create a new repository
- Click the **+** icon → **New repository**
- Name it `quantara` (or anything you like)
- Set it to **Public**
- Click **Create repository**

### Step 3 — Upload your files
- Click **"uploading an existing file"** on the repo page
- Drag all files from the `quantara` folder (including the `css` subfolder)
- Click **"Commit changes"**

### Step 4 — Enable GitHub Pages
- Go to **Settings → Pages**
- Under "Source" select **Deploy from a branch**
- Select branch: `main`, folder: `/ (root)`
- Click **Save**

Your site will be live at:
`https://YOUR-USERNAME.github.io/quantara/`

It may take 1–2 minutes to go live the first time.

---

## Option C: Custom domain (after deploying to Netlify or GitHub Pages)

1. Buy a domain at Namecheap, Porkbun, or Google Domains (~$10–15/yr)
   Suggested: `quantara.ca` or `quantara.io`
2. In Netlify: Site settings → Domain management → Add custom domain
3. In your domain registrar: point the nameservers to Netlify's (they'll show you the values)
4. SSL certificate is applied automatically — your site will be `https://quantara.ca`

---

## Next steps after going live

- Add Google Analytics (free) to track visitors
- Submit your sitemap to Google Search Console
- Start adding real affiliate links from Ratehub or bank partner programs
- Begin posting Reels/TikToks with your site link in bio
