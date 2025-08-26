# Typography Test — Outfit (px + Container Queries)

**What this is**
- Outfit font (Google Fonts)
- Titles: semi‑bold (600), Body: regular (400)
- Font sizes in px for consistent visual size
- Container queries for responsive layout that **doesn't flip to tablet** at high desktop zoom
- Visual container width indicators

**Deploy to GitHub Pages**
1) Push `index.html` and `style.css` to your repo root.
2) Settings → Pages → Source: `main` + `/ (root)` → Save.
3) Visit: `https://<your-username>.github.io/<repo>/`

**Tweak type sizes**
Edit the variables at the top of `style.css`:
```
:root{
  --h1:64px; --h2:48px; --h3:36px; --h4:28px; --h5:22px; --h6:18px;
  --body-lg:18px; --body:16px; --body-sm:14px; --caption:12px;
}
```
