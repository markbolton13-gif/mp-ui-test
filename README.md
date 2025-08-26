# Typography Test — Outfit (px + Container Queries, with Font Scaling)

This project demonstrates a **zoom-safe, container-based responsive typography system** using the [Outfit](https://fonts.google.com/specimen/Outfit) font.

---

## ✅ Features
- **Fonts**
  - Outfit from Google Fonts
  - Titles: **semi-bold (600)**
  - Body: **regular (400)**
  - Base font sizes in **px** (don’t scale with zoom)  

- **Zoom-safe layout**
  - Uses **container queries**, not viewport media queries  
  - ✅ On **desktop at 250% zoom** → layout **stays desktop**  

- **Breakpoints (container-based)**
  - **≤ 1024px** → 2 columns *(tablet)* + reduced font sizes  
  - **≤ 800px** → 2 columns *(tight squeeze layout)*  
  - **≤ 520px** → 1 column *(mobile)* + reduced font sizes  

- **Font scaling at smaller widths**
  - Tablet: H1 → 52px (down from 64px), other sizes adjusted proportionally  
  - Mobile: H1 → 42px, H2 → 32px, etc.  
  - Body text also scales down slightly for readability  

- **Extras**
  - Visual **container width indicators** (40ch, 60ch, 70ch, 80ch, 960px)  
  - Demo layout block showing container-query behavior  

---

## 📂 Files
- `index.html` → typography specimens + layout demo  
- `style.css` → design tokens, typography scale, container queries  
- `README.md` → this guide  

---

## 🚀 Deploy on GitHub Pages
1. Upload `index.html` and `style.css` to the root of your repo.  
2. In your repo: **Settings → Pages**  
   - Source: **Deploy from a branch**  
   - Branch: `main`  
   - Folder: `/ (root)`  
3. Save → wait 1–2 minutes.  
4. Open:  
