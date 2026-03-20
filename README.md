# 🔴 PRO DIP LLC — Website Pitch

> **Window Tint & Paint Wraps · Quincy, IL**  
> Built by [DTE Solutions](https://dtesolutions.io) · Designed to convert, built to rank.

---

## 🏆 About the Client

| | |
|---|---|
| **Business** | Pro Dip LLC |
| **Owner** | Ahmed Fayed |
| **Location** | 1704 N. 24th St, Suite 6 · Quincy, IL 62301 |
| **Phone** | (217) 257-7791 |
| **Email** | ahmedfayed@prodipqcy.com |
| **Facebook** | [prodipgarage.LLC](https://www.facebook.com/prodipgarage.LLC) |
| **Instagram** | [@prodipllc](https://www.instagram.com/prodipllc/) |
| **Awards** | 🏆 Best Window Tint Shop — Quincy **2025 & 2026** |

**Services:** Ceramic Window Tint · Full & Partial Paint Wraps · Paint Protection Film (PPF)  
**Vehicles:** Cars · Trucks · Motorcycles · ATVs / UTVs

---

## ⚡ What's Built

Single-file production pitch page (`prodip3.html`) — no framework, no dependencies, no build step. Open it in a browser and it works.

### Features

- **Animated neon hero** — scan lines, pulsing red orb, staggered reveal animations
- **Scrolling ticker** — awards, services, phone number on loop
- **Service cards** — 4 vehicle-only services with custom SVG line icons and neon hover states
- **Tabbed before/after slider** — one drag slider with 4 vehicle tabs (Car, Truck, Motorcycle, ATV). Each tab has its own custom SVG vehicle icon. Swap in real photos per panel.
- **Bento gallery** — asymmetric 12-column CSS grid, 9 cells with labeled placeholders. Drop real job photos in.
- **Testimonials** — 6 real verified Google reviews with vehicle + name attribution
- **Google Review CTA** — direct deep-link to Ahmed's review form (requires Place ID swap)
- **Missed call contact form** — fires a pre-formatted `mailto:` to Ahmed's inbox on submit. Zero backend.
- **Neon footer socials** — Facebook (blue glow) + Instagram (pink glow) with pulsing LIVE badge
- **Full SEO package** — LocalBusiness schema, meta tags, Open Graph, canonical, robots
- **Scroll reveal** — IntersectionObserver fade-up on all sections
- **Fully responsive** — mobile-first breakpoints at 640px and 900px

---

## 🛠 Tech Stack

```
HTML5 · CSS3 · Vanilla JS
Google Fonts — Rajdhani + Exo 2
Zero npm · Zero frameworks · Zero build step
```

---

## 📁 File Structure

```
prodip3.html      ← entire site, single file, ready to deploy
README.md         ← you're here
```

---

## 🚀 Deployment Options

### Option A — Netlify Drop (fastest, free)
1. Go to [netlify.com/drop](https://app.netlify.com/drop)
2. Drag `prodip3.html` onto the page
3. Live in 30 seconds. Rename to `index.html` first for clean URLs.

### Option B — Vercel
```bash
npx vercel --name prodip
```

### Option C — GitHub Pages
```bash
git init
git add prodip3.html
git commit -m "init"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/prodip.git
git push -u origin main
# Enable Pages in repo Settings → Pages → Deploy from main
```

### Option D — Custom Domain (recommended for client)
Point `prodipqcy.com` DNS to whichever host above. Add SSL (free on all three).

---

## ✅ Before You Launch — Checklist

### Required
- [ ] **Swap Google Place ID** in the review button URL
  ```
  https://search.google.com/local/writereview?placeid=YOUR_PLACE_ID_HERE
  ```
  → Get it at `developers.google.com/maps/documentation/javascript/examples/places-placeid-finder`

- [ ] **Add real photos** to the bento gallery (replace `.b-ph` placeholder divs with `<img>` tags)

- [ ] **Add real before/after photos** — set `background-image` on `.s-before` and `.s-after` per tab panel

- [ ] **Update business hours** if different from Mon–Fri 9:30am–5:00pm

### Recommended
- [ ] Submit to Google Search Console
- [ ] Verify ownership → submit sitemap
- [ ] Set up Google Business Profile if not already active
- [ ] Create `og-image.png` (1200×630px) for social sharing previews
- [ ] Replace placeholder review count in schema (`"reviewCount": "111"`) with live number

---

## 📸 Adding Real Photos

### Bento Gallery
Replace any `.b-ph` div inside a `.b-cell` with:
```html
<img src="your-photo.jpg" alt="Ceramic tint — 2022 Ford F-150" style="width:100%;height:100%;object-fit:cover;" />
```

### Before/After Slider
On the `.s-before` and `.s-after` divs, add inline style:
```html
<div class="s-before" style="background-image:url('before.jpg');background-size:cover;background-position:center;">
```
The SVG icon and label text will layer on top — remove them if you want a clean photo-only slider.

---

## 🔍 SEO — What's Baked In

| Element | Status |
|---|---|
| `<title>` tag | ✅ Keyword-optimized |
| Meta description | ✅ 155 chars, action-oriented |
| Canonical tag | ✅ Set (update domain) |
| Open Graph tags | ✅ Title, description, type |
| LocalBusiness schema | ✅ Address, hours, phone, socials, rating |
| `AutoRepair` schema type | ✅ More specific than generic LocalBusiness |
| Mobile responsive | ✅ 640px + 900px breakpoints |
| Semantic HTML | ✅ Sections, nav, footer, headings |
| robots meta | ✅ index, follow |

**Next step after launch:** Get Ahmed's past customers to leave Google reviews using the review deep-link. Every 5-star review with a vehicle mentioned ("tinted my Silverado") is a free long-tail keyword for local SEO.

---

## 💰 Monthly Retainer Pitch — What You're Selling Ahmed

| Deliverable | Details |
|---|---|
| Hosting & domain management | Keep the site live, SSL renewed, uptime monitored |
| Photo updates | New job photos → bento gallery updated monthly |
| Review management | Send review request link to completed customers |
| Google Search Console monitoring | Crawl errors, Core Web Vitals, indexing issues |
| Seasonal promos | Landing page updates for promotions or new services |
| Social link maintenance | Keep FB/IG links current |
| SEO reporting | Monthly rank snapshot for target keywords |

**Suggested pricing:** $150–$250/month depending on scope. One new customer from the site pays for 6 months.

---

## 🤝 Built By

**DTE Solutions LLC**  
Quincy, IL · [dtesolutions.io](https://dtesolutions.io)  
Full-stack development · AI products · Data engineering

---

*Pitch confidently. The site sells itself.*
