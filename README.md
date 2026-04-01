# April Fools 2026 — Production-Ready Prank Pages

Two highly polished, fully self-contained HTML/CSS/JS prank pages designed to look like authentic news media and official corporate product launches.

## 📂 Files

- **`index.html`** — Landing page with links to both prank pages
- **`news-article.html`** — Reuters-style breaking news article
- **`google-homes.html`** — Google product launch landing page
- **`README.md`** — This file

## 🎭 Pages Included

### 1. Reuters Breaking News (`news-article.html`)

A production-grade financial news article announcing Google's surprise launch of **"Google Homes"** — an AI-powered property discovery platform.

**Features:**
- Live stock ticker at top (animated marquee)
- Authentic Reuters layout, branding & typography
- Navigation bars, breadcrumbs, bylines
- Full article body with multiple sections
- Professional stock price table
- Market reaction quotes from real analysts
- Share buttons (X, LinkedIn, Email)
- Newsletter signup widget
- "Most Read" sidebar
- Related articles
- Responsive design (mobile-friendly)

**Realism Details:**
- Publication timestamp: April 1, 2026 · 08:01 CET
- Author: Reuters Staff
- Real company tickers (RMV.L, Z, CSGP, REA.AX, GOOGL)
- Realistic market data in tables
- Subtle April Fools hint in editor's note

### 2. Google Homes Product Page (`google-homes.html`)

An official-looking Google product landing page for "Google Homes" inspired by Google's real product launches.

**Features:**
- Google-style design & branding (colorful logo grid)
- Beta announcement banner (dismissible)
- Sticky navigation with smooth scrolling
- Large hero section with animated CSS illustration
  - Interactive map mockup with pins & floating property cards
  - Live pulse animation
- Feature overview cards (3 columns)
- Deep-dive sections with alternating layouts:
  - *Beschikbaarheidsmodule* (availability module)
  - *Aanbod pagina* (listings page)
  - *Filters* (interactive UI mockup)
- Real-time notification card mockups
- Interactive filter panel with working range sliders
- Animated stats counter section
- Testimonials from beta users
- Industry impact quote section
- Market availability grid
- "For Business" partnership section
- Large CTA section with toast notification
- Professional footer with links
- Smooth scroll animations & fade-in effects
- Fully responsive (mobile, tablet, desktop)

**Realism Details:**
- Google color palette (Blue, Red, Yellow, Green)
- Authentic Google UI patterns
- Comprehensive product description
- Translated terms: beschikbaarheidsmodule, aanbod pagina, filters
- Market-specific info (US, UK, Netherlands, Australia)
- Professional testimonials

## 🚀 GitHub Pages Setup

### Option 1: Deploy from Root (Recommended)

1. Ensure the repository is at the root directory `/Users/jelmarbosscher/Documents/Projects/Reddstone/JELMAR/experiments/fools`
2. Go to your GitHub repository **Settings → Pages**
3. Under "Source", select **Deploy from a branch**
4. Choose **main** (or your default branch) and **/root** (or no `/docs` folder)
5. Click **Save**
6. GitHub will deploy the files to `https://your-username.github.io/fools/`

### Option 2: Deploy from `/docs` Folder

If you prefer organizing in a `/docs` folder:

1. Create a `/docs` folder in the repository
2. Move all files (HTML, etc.) into `/docs`
3. Go to **Settings → Pages**
4. Select **Deploy from a branch** → **main** → **/docs**
5. Save

### Option 3: GitHub Actions (Advanced)

For automatic deployments, create `.github/workflows/deploy.yml`:

```yaml
name: Deploy to GitHub Pages
on:
  push:
    branches: [main]
jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Deploy
        uses: peaceiris/actions-gh-pages@v3
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          publish_dir: ./
```

## 📋 File Structure

```
fools/
├── index.html              # Landing page (entry point)
├── news-article.html       # Reuters breaking news prank
├── google-homes.html       # Google product page prank
├── README.md              # This file
├── .gitignore             # Git ignore rules
└── .git/                  # Git repository
```

## 🌐 Live URL

Once deployed to GitHub Pages, your prank pages will be live at:

- **Landing page:** `https://your-username.github.io/fools/`
- **News article:** `https://your-username.github.io/fools/news-article.html`
- **Google product page:** `https://your-username.github.io/fools/google-homes.html`

## ⚙️ Technical Stack

- **HTML5** — Semantic markup
- **CSS3** — No frameworks, all custom styling
- **Vanilla JavaScript** — No dependencies
- **Responsive Design** — Mobile-first, works on all devices
- **Zero External Dependencies** — Fonts from Google Fonts CDN (optional; can be removed)

## 📱 Browser Support

- Chrome/Brave 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Customization

All styling is inline or in `<style>` tags. To customize:

1. **Colors:** Search for CSS variables (`:root`) or hex colors
2. **Text:** Edit HTML content directly
3. **Layout:** Modify grid templates or flexbox properties
4. **Typography:** Adjust font sizes, weights, letter-spacing

## 📝 Notes

- Both pages are **fully self-contained** — no external assets or APIs
- **No backend required** — pure static HTML/CSS/JS
- **SEO-friendly** — proper meta tags, semantic HTML
- **Accessibility** — alt text, proper heading hierarchy, ARIA labels
- **Performance** — optimized CSS, no render-blocking scripts

## 🪓 Important

These pages are designed as **April Fools pranks**. They are highly believable but clearly labeled as pranks when used responsibly. Use them for entertainment purposes only.

### Ethical Usage

- ✅ Share with friends/colleagues who enjoy pranks
- ✅ Use as portfolio/demo of web design skills
- ✅ Educational purposes (learning HTML/CSS/JS)
- ❌ Do NOT use to deceive or defraud
- ❌ Do NOT spread misinformation as real news
- ❌ Do NOT use for malicious purposes

## 📄 License

These prank pages are open-source and free to use, modify, and share.

---

**Created:** April 1, 2026  
**Status:** Production-ready for GitHub Pages  
**Updated:** Ready for deployment
