# Ellie's Connect — Website Rebuild

A clean, fast, hand-coded rebuild of elliesconnect.com (previously on Squarespace), preserving your brand — cream/burgundy/gold palette, serif typography, "Depth. Discretion. Decades." positioning — while fixing structural gaps and adding real SEO fundamentals.

## What's here

- `index.html` — Home
- `advisory.html` — Pre-Acquisition, Acquisition, Post-Acquisition (previously three separate near-empty Squarespace pages, consolidated into one page with anchors so search engines see one strong page instead of three thin ones)
- `capitals.html` — New York, London, Dubai (the originals were blank "Headline / Body Text" placeholders — I wrote real content for each)
- `about.html` — About Ellie (copy carried over as-is)
- `manhattan-neighborhoods.html` — the six neighborhoods listed on your old site, now with actual descriptions (the original page only showed names)
- `market-insights.html` — your Foreign Buyer Activity report. Note: your old site had this report duplicated under two different nav labels ("2024-2025" and "2022-2024") with identical content — I merged it into a single accurate page.
- `zh.html` — 中文服务, content carried over
- `css/style.css`, `js/main.js` — shared styling and the mobile-menu/contact-form behavior
- `sitemap.xml`, `robots.txt` — for search engine indexing

## Before this goes live

1. **Contact form.** It's wired for [Netlify Forms](https://docs.netlify.com/manage/forms/setup/) (zero backend needed if you host on Netlify) and falls back to opening the visitor's email client if not deployed there. Swap in your preferred backend (Netlify, Formspree, etc.) if you host elsewhere — search `data-netlify` and `mailto:hello@elliesconnect.com` in the HTML.
2. **Logo.** I rebuilt a simple key-mark placeholder in the header since I couldn't extract your original logo file from Squarespace. Drop in your real logo image and swap the inline SVG.
3. **Images.** This build is text/layout only — no photography was pulled from the old site. Add property/lifestyle photography for real visual impact (this matters a lot for a luxury real estate brand).
4. **Domain & hosting.** Point elliesconnect.com at wherever you deploy this (Netlify, Vercel, or any static host) once you're ready to leave Squarespace.
5. **Email address.** I used `hello@elliesconnect.com` as a placeholder in the contact section — update if different.

## Why this will perform better than the Squarespace version

- Real `<title>` and meta description on every page (the Squarespace site had generic/duplicate titles)
- Structured data (schema.org) so Google understands this is a real estate advisory business
- No Squarespace JS/CSS bloat — pages load fast, which Google factors into ranking
- Fixed the duplicate-content issue between the two "Foreign Buyer Activity" pages, which actively hurts SEO
- Filled in three pages (New York, London, Dubai) that were previously blank and indexable — blank indexed pages hurt overall site quality signals
- Semantic HTML structure (proper heading hierarchy, one H1 per page) that Squarespace's page builder doesn't reliably produce

Design/code quality gets you found and gets people to stay. Ranking well also depends on backlinks, Google Business Profile, and ongoing content — happy to help with that next.
