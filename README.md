# BuyMeWebsite.com

Landing page for **BuyMeWebsite.com** — an affordable website design & development service for businesses, schools, colleges, restaurants, doctors, lawyers, real estate, and NGOs across India. Websites start from ₹5,000 with domain, hosting, and SSL included.

🔗 Live site: [buymewebsite.com](https://buymewebsite.com/)

## About

This repo is a single, self-contained static landing page (`index.html`) built to convert visitors into leads. It covers:

- **Pricing** — tiered packages from portfolio sites to full e-commerce/SaaS builds
- **What's included** — domain, hosting, and SSL for the first year
- **Process** — how a project goes from discovery call to launch
- **Industries served** — schools, restaurants, doctors, lawyers, real estate, NGOs, and more
- **Team** — the people behind the studio
- **FAQ** — pricing, payment plans, delivery timelines, and support
- **Contact** — ways to get in touch and start a project

## Tech Stack

- Plain **HTML5** — no build step, no framework
- **Tailwind CSS** (via CDN) for styling
- **Google Fonts** (Syne + Outfit) and **Font Awesome** for icons
- Vanilla JS for scroll reveals, a marquee, and the custom cursor
- JSON-LD structured data (`ProfessionalService`, `WebSite`, `FAQPage`) for SEO

## Project Structure

```
.
├── index.html           # The entire site (markup, styles, and scripts)
├── favicon.svg           # Site favicon
├── og-cover-source.html  # Source template used to generate the Open Graph cover image
├── images/                # Team photos and the OG cover image
├── robots.txt             # Search engine crawl rules
├── sitemap.xml             # Sitemap for search engines
└── README.md
```

## Running Locally

No build tools or dependencies required — it's a static page.

```bash
# Clone the repo
git clone https://github.com/adityagupta29/buymewebsite.com.git
cd buymewebsite.com

# Open directly in a browser
open index.html   # macOS
start index.html   # Windows
```

Or serve it locally for a closer-to-production feel:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

The site is a static page and can be deployed as-is to any static host (e.g. GitHub Pages, Netlify, Vercel, Cloudflare Pages). Just point the host at the repo root — no build command needed.

## Contact

For business inquiries, reach out via the contact section on the [live site](https://buymewebsite.com/) or email heyaditya29@gmail.com.
