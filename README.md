# Stitch Your Love — Mother's Day Embroidery Catalog
# Cloudflare Pages + GitHub Deployment

## 🚀 Quick Deployment to Cloudflare Pages via GitHub

### Step 1 — Create a new GitHub repo
1. Go to https://github.com/dimkaits777
2. Click **New repository**
3. Name it: `mothers-day-embroidery` (or similar)
4. Set to **Public**
5. Click **Create repository**

### Step 2 — Add the video file
- Copy your video file `banner_Mother_s_Day.mp4` into the `/assets/` folder
- Rename it to: `banner_mothers_day.mp4`
- Commit and push all files to GitHub

### Step 3 — Connect to Cloudflare Pages
1. Go to https://dash.cloudflare.com
2. Click **Pages** → **Create a project** → **Connect to Git**
3. Select your GitHub account and choose the repository
4. Build settings:
   - **Framework preset**: None (static HTML)
   - **Build command**: *(leave empty)*
   - **Build output directory**: `/` (root)
5. Click **Save and Deploy**

### Step 4 — Done! 🎉
Cloudflare Pages will give you a free URL like:
`https://mothers-day-embroidery.pages.dev`

---

## 📁 File Structure
```
/
├── index.html          ← Homepage with hero video, categories, quiz
├── shop.html           ← Full product catalog with sidebar filters
├── gift-guide.html     ← Blog / gift guide article
├── style.css           ← All styles (glassmorphism, animations)
├── products.js         ← All product data from CSV
├── _redirects          ← Cloudflare routing rules
└── assets/
    └── banner_mothers_day.mp4   ← Hero video (YOU MUST ADD THIS)
```

---

## 🎨 Design System
- **Font**: Great Vibes (script headlines) + Playfair Display (serif) + Outfit (sans)
- **Colors**: Cool Blue → Jade gradient bg, Plum Noir text, Wasabi green CTAs, Persimmon orange accents
- **Effects**: Glassmorphism cards, sticky scroll-hide navbar, thread stitch progress line, scroll reveal animations
- **Features**: Wishlist (localStorage), Gift Finder Quiz, Category filters, Trending carousel

---

## 📊 SEO
- Meta title + description on each page
- JSON-LD structured data on homepage
- Semantic HTML with proper heading hierarchy
- Lazy-loaded images
- Product titles follow pattern: "[Design Name] Machine Embroidery Design | Mother's Day"

---

## 🔗 Affiliate Links
All product links use your affiliate ref: `ref/20531415/`
General collection link: https://www.creativefabrica.com/search/ref/20531415/?query=mother&type=Embroidery
