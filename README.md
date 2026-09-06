# Arun Enterprises — Driver Mitra website

Static site for GitHub Pages: landing page + Razorpay policy pages.

## Files
- `index.html` — landing page (Download App button)
- `terms.html`, `privacy.html`, `refund.html`, `shipping.html`, `contact.html` — policy pages
- `styles.css` — shared styles
- `.nojekyll` — serve files as-is on GitHub Pages

## Before you go live — fill these in
Replace every `[bracketed placeholder]` (shown in orange on the pages) across the
policy pages: office address, phone, email, dates, city/state, refund window.
Have the policy wording reviewed for your business before relying on it.

## Publish to GitHub Pages

1. Create an empty repo on github.com (e.g. `arun-enterprises-site`). Do NOT add a README there.
2. In a terminal:

```powershell
cd D:\arun-enterprises-site
git config --global user.name "Your Name"          # only needed once
git config --global user.email "you@example.com"   # only needed once
git init
git branch -M main
git add .
git commit -m "Arun Enterprises website"
git remote add origin https://github.com/<USERNAME>/<REPO>.git
git push -u origin main
```

3. On github.com: repo → **Settings** → **Pages** → Source: **Deploy from a branch**
   → Branch: **main**, folder **/ (root)** → **Save**. Live in ~1 minute at
   `https://<USERNAME>.github.io/<REPO>/`.

## Updating later
```powershell
cd D:\arun-enterprises-site
git add .
git commit -m "Update site"
git push
```
