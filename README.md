# Typography Test — Outfit (px + Container Queries, with 1024px tablet)

**What you get**
- Outfit font via Google Fonts
- Titles: semi‑bold (600); Body: regular (400)
- Font sizes in **px** (consistent visual size)
- **Container queries** so desktop at **250% zoom stays desktop**
- Breakpoints (container-based, zoom-safe):
  - ≤ **1024px** → 2 columns (tablet)
  - ≤ **800px** → 2 columns (tight squeeze)
  - ≤ **520px** → 1 column (mobile)
- Visual container width indicators (40ch, 60ch, 70ch, 80ch, 960px)

**Deploy on GitHub Pages**
1) Upload `index.html` and `style.css` to the repo root.  
2) Settings → Pages → Source: `main` + `/ (root)` → Save.  
3) Visit: `https://<your-username>.github.io/<repo>/`.

**Tweak type sizes**
Edit the variables in `style.css`:
```
:root{
  --h1:64px; --h2:48px; --h3:36px; --h4:28px; --h5:22px; --h6:18px;
  --body-lg:18px; --body:16px; --body-sm:14px; --caption:12px;
}
```
