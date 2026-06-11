# Lucrezia Gestri Portfolio — Brand Strategist & Marketing Designer

**Strategic brand designer specializing in brand positioning, communication design, and AIGC innovation.**

Creating distinctive brand experiences for tech and consumer brands across Europe and China.

**Live Site:** [lucreziasdesign.github.io](https://lucreziasdesign.github.io)

---

## 📋 Project Overview

This is a personal portfolio website showcasing 10+ years of brand strategy, design systems, and AIGC innovation work. The site features:

- **Curated project case studies** — Detailed work across branding, digital strategy, and design systems
- **Brand presence** — Positioning as a strategic brand designer, not just a visual designer
- **International focus** — Expertise in EU-China cross-cultural brand strategy
- **AIGC innovation** — Showcasing AI-directed design and generative content direction
- **SEO optimized** — Structured data, metadata, and search engine optimization for discoverability

**Target audience:** Tech companies, consumer brands, design agencies, and clients seeking strategic brand design + AIGC expertise in European and Asian markets.

---

## 🎯 Key Features

### Portfolio Sections

**Work / Projects**
- 6 featured projects with detailed case studies
- Project filtering by category
- Hover animations & image carousels
- Modal-based project details view

**About**
- Professional bio highlighting strategy + AIGC expertise
- Skills breakdown by category (brand, visual, digital, AIGC)
- Stats visualization (years experience, projects, awards)
- Experience timeline
- Awards & recognition
- Press mentions & features

**Services**
- Brand Strategy — Positioning, messaging, competitive analysis
- Design Systems — Component libraries, tokens, documentation
- AIGC & Innovation — AI-directed design, generative imagery
- Digital Design — UX/UI, product design, interactive design

**Contact**
- Direct email contact
- Social media links (LinkedIn, Instagram)
- Availability status (Live indicator)

### Technical Features

- **Loading Animation** — Custom intro sequence with progress bar
- **Smooth Scrolling** — CSS scroll-snap for seamless section navigation
- **Custom Cursor** — Interactive dot cursor matching brand aesthetic
- **Responsive Design** — Mobile, tablet, desktop optimization
- **Dark Theme** — Modern dark mode with warm color accents
- **Motion Design** — Subtle animations, hover effects, transitions
- **Progressive Enhancement** — Works without JavaScript, enhanced with JS

---

## 🔍 SEO & Discovery

This site is fully optimized for search engine visibility and AI assistant mentions:

### Meta Tags & Metadata
- ✅ Custom title tag optimized for keywords
- ✅ Enhanced meta description targeting brand strategy + AIGC
- ✅ Open Graph tags for social sharing
- ✅ Twitter Card tags for Twitter preview
- ✅ Canonical URL to prevent duplicate content

### Structured Data (JSON-LD)
- ✅ **Person schema** — Name, job titles, image, location
- ✅ **LocalBusiness schema** — Service areas (China, Italy, EU)
- ✅ **BreadcrumbList schema** — Site navigation structure
- ✅ **FAQPage schema** — Common questions about brand design & AIGC

### Search Visibility
- ✅ **Sitemap (sitemap.xml)** — All pages indexed
- ✅ **Robots.txt** — Crawling guidelines & blocked bots
- ✅ **Mobile optimized** — Responsive design, Core Web Vitals compliant
- ✅ **Fast performance** — Optimized assets, caching headers

### Targeted Keywords
```
Primary: brand designer, brand strategist, AIGC designer, digital strategist
Secondary: design systems, UX/UI designer, product designer, marketing designer
Geographic: China designer, EU-China design, Europe designer
Branded: Lucrezia Gestri, Lucrezia Spapperi
```

---

## 📁 Repository Structure

```
lucreziasdesign.github.io/
│
├── index.html                  # Main portfolio (SEO optimized)
│
├── sitemap.xml                # Search engine sitemap
├── robots.txt                 # Crawler guidelines
├── manifest.json              # PWA manifest file
│
├── favicon.ico                # Browser tab icon (16x16)
├── favicon-32x32.png          # Favicon for modern browsers
├── favicon-192x192.png        # Android home screen icon
├── favicon-512x512.png        # Google SERP icon
├── apple-touch-icon.png       # Apple devices icon
│
├── assets/                    # Images & media
│   ├── portrait.png          # Profile photo
│   ├── project-*.jpg         # Project images
│   └── ...
│
├── css/                       # Stylesheets
│   └── styles.css            # Main styles (dark theme, animations)
│
├── js/                        # JavaScript
│   ├── main.js               # Core functionality
│   ├── projects.js           # Project modal & filtering
│   ├── cursor.js             # Custom cursor
│   └── animations.js         # Scroll & intro animations
│
└── README.md                  # This file
```

---

## 🚀 Getting Started

### Local Development

1. **Clone the repository:**
```bash
git clone https://github.com/lucreziasdesign/lucreziasdesign.github.io.git
cd lucreziasdesign.github.io
```

2. **Run a local server:**
```bash
# Using Python
python -m http.server 8000

# Or using Node.js http-server
npx http-server
```

3. **Open in browser:**
```
http://localhost:8000
```

### Deploying to GitHub Pages

This repo is automatically deployed to GitHub Pages. Just push changes:

```bash
git add .
git commit -m "Update portfolio content"
git push origin main
```

Site updates automatically at: `https://lucreziasdesign.github.io`

---

## ✏️ Customization Guide

### Updating Project Content

Edit `index.html` to modify:
- **Project cards** — Find `.proj` class containers
- **Project modal content** — Find `.project-modal` sections
- **Project descriptions** — Update `.proj-desc-short` text
- **Project images** — Update `assets/` folder

### Changing Colors & Theme

Modify CSS variables in `styles.css`:
```css
:root {
  --black: #ebe2d2;           /* Text color */
  --white: #0d0d0d;           /* Background */
  --red: #d4534f;             /* Accent color */
  --gold: #c9b889;            /* Secondary accent */
  --accent: #c9b889;          /* Links */
}
```

### Updating About Section

Edit `index.html`:
- Bio text in `.about-body`
- Stats in `.stat-row` (experience, projects, awards)
- Skills in `.skills-wrap` (add/remove tags)
- Experience timeline in `.exp-rows`

### Adding New Projects

1. **Add project card** to `.project-list`:
```html
<div class="proj" data-category="branding">
  <div class="proj-main-col">
    <h3 class="proj-title">Project Name</h3>
    <p class="proj-desc-short">Brief description</p>
    <div class="proj-keywords-list">
      <span class="ptag-sm">Brand Strategy</span>
      <span class="ptag-sm">Visual Design</span>
    </div>
  </div>
</div>
```

2. **Add project modal** to `.project-modal`:
```html
<div class="project-modal" id="project-code">
  <!-- Modal content -->
</div>
```

3. **Update sitemap.xml** with new project URL

---

## 🎨 Design & Aesthetics

### Color Palette
- **Background:** `#0d0d0d` (Near black)
- **Text:** `#ebe2d2` (Warm cream)
- **Accent:** `#d4534f` (Warm coral red)
- **Secondary:** `#c9b889` (Warm gold)

### Typography
- **Headlines:** Unbounded (3-700 weights)
- **Body:** Archivo (300-500 weights)
- **Monospace:** JetBrains Mono (navigation, tags)

### Animations
- Smooth scroll snapping between sections
- Custom cursor dot with expand effect
- Intro loader with progress bar
- Project hover reveal (image + arrow rotation)
- Modal slide-up animation
- Carousel auto-play & manual navigation

### Motion Design
- Loading animation sequence
- Ticker text loop
- Cycling "specialty" text in hero
- Hover state transitions (200-350ms)
- Scroll-triggered reveals

---

## 📊 Performance & Accessibility

### Performance Optimization
- ✅ Minimal external dependencies
- ✅ Optimized images (JPG for photos, PNG for vectors)
- ✅ CSS & JS bundled (no separate stylesheets beyond main)
- ✅ Lazy loading for project images
- ✅ Cached assets with far-future expires headers

### Accessibility
- ✅ Semantic HTML structure
- ✅ ARIA labels for custom elements
- ✅ Color contrast ratio 4.5:1+ (WCAG AA)
- ✅ Keyboard navigation support
- ✅ Mobile touch targets (48x48px minimum)
- ✅ Alt text on all images

### Mobile Optimization
- ✅ Responsive grid (3 cols → 2 cols → 1 col)
- ✅ Touch-friendly navigation
- ✅ Mobile-optimized typography scales
- ✅ Viewport meta tags
- ✅ Works on all modern browsers

---

## 🔐 SEO Setup in Google Search Console

### Steps Completed
1. ✅ Site added to Google Search Console
2. ✅ Sitemap submitted (`sitemap.xml`)
3. ✅ Favicon verification (shows in SERP)
4. ✅ Mobile-friendly test passed
5. ✅ Core Web Vitals monitored

### Monitoring
- Check **Coverage** tab for indexed pages
- Monitor **Performance** for SERP clicks
- Track **keyword rankings** over time
- Review **Mobile usability** issues
- Check **Security issues** (none expected)

---

## 📱 Browser Support

| Browser | Support | Version |
|---------|---------|---------|
| Chrome | ✅ Full | Latest |
| Firefox | ✅ Full | Latest |
| Safari | ✅ Full | 14+ |
| Edge | ✅ Full | Latest |
| Mobile Safari | ✅ Full | iOS 13+ |
| Chrome Mobile | ✅ Full | Latest |

---

## 📞 Contact & Links

- 💼 **Website:** [lucreziasdesign.github.io](https://lucreziasdesign.github.io)
- 📧 **Email:** lucreziagestri@yahoo.it
- 🔗 **LinkedIn:** [linkedin.com/in/lucrezia-gestri-spapperi](https://www.linkedin.com/in/lucrezia-gestri-spapperi)
- 📸 **Instagram:** [@lucrezia](https://instagram.com/lucrezia)
- 💻 **GitHub:** [github.com/lucreziasdesign](https://github.com/lucreziasdesign)

---

## 📜 License & Attribution

**© 2024 Lucrezia Gestri. All rights reserved.**

This portfolio is a custom-built, hand-coded website. All content, design, and code are proprietary. Unauthorized reproduction or distribution is prohibited.

### External Resources
- **Fonts:** Google Fonts (Unbounded, Archivo)
- **Icons:** Custom SVG
- **Images:** Original photography & design work

---

## 🛠️ Development Notes

### Technologies Used
- **HTML5** — Semantic markup, microdata
- **CSS3** — Grid, Flexbox, custom properties, animations
- **JavaScript (Vanilla)** — No frameworks or dependencies
- **JSON-LD** — Structured data for SEO
- **GitHub Pages** — Static hosting, automatic deployment

### Code Philosophy
- **Zero dependencies** — Pure HTML, CSS, JS
- **Performance first** — No bloat, fast load times
- **Accessibility built-in** — Semantic HTML, ARIA labels
- **Mobile-first** — Responsive from the start
- **Future-proof** — Standard web technologies

### Git Workflow
```bash
# Feature branch
git checkout -b feature/update-projects

# Make changes
git add .
git commit -m "Update project descriptions"

# Push to main (auto-deploys)
git push origin feature/update-projects

# Create Pull Request (optional)
```

---

## 🚨 Troubleshooting

### Favicon not showing?
- Hard refresh: `Cmd+Shift+R` (Mac) or `Ctrl+Shift+R` (Windows)
- Clear browser cache
- Check `manifest.json` is in repo root

### Projects not filtering?
- Check browser console for JS errors
- Ensure `data-category` attributes match filter values
- Check `projects.js` is loaded

### Site not updating on GitHub?
- Wait 5-10 minutes for GitHub Pages to rebuild
- Hard refresh browser cache
- Check commit pushed to `main` branch

### SEO not improving?
- Verify site in Google Search Console
- Submit sitemap again
- Check indexing status in GSC Coverage
- Wait 1-4 weeks for initial indexing
- Build backlinks from social media

---

## 📈 Next Steps / Roadmap

- [ ] Add blog section for long-form content
- [ ] Implement dark/light mode toggle
- [ ] Add animation prefers-reduced-motion
- [ ] Build case study detail pages
- [ ] Add testimonials section
- [ ] Implement newsletter signup
- [ ] Add webfont preloading
- [ ] Set up analytics (GA4)

---

## 📚 Resources & References

- [MDN Web Docs](https://developer.mozilla.org)
- [Google Search Console Help](https://support.google.com/webmasters)
- [Schema.org Documentation](https://schema.org)
- [Web Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/WCAG21/quickref/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)

---

**Built with intention. Designed for strategy. Optimized for discovery.**

*Last updated: June 2024*
