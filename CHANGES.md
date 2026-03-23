# MoneyTab.in — SEO & Bug Fix Summary

## Files Changed
Replace all .html files and css/style.css in your GitHub repo with these.
Images do NOT need to change — only folder references in HTML were fixed.

---

## 🔴 Critical Bugs Fixed

### 1. Broken Image Paths (ALL pages)
Images were in `images/shared/`, `images/gold-loan/`, `images/two-wheeler/` etc.
but HTML referenced them as `images/filename.jpg` (flat path). All fixed.

**Files affected:** index.html + all 7 article pages

### 2. Missing Canonical Tags (ALL pages)
Every page was missing `<link rel="canonical">` — this causes duplicate content
penalties with Google. All 20 pages now have canonical URLs.

### 3. Missing Open Graph Tags (ALL pages)
No `og:type`, `og:url`, `og:image`, `og:description` on any page.
WhatsApp/Facebook/Twitter link previews were broken. All fixed.

### 4. Missing Twitter Card Tags (ALL pages)
No `twitter:card` meta tags on any page. Twitter link previews broken. Fixed.

### 5. Missing JSON-LD Structured Data (ALL pages)
No schema.org markup anywhere — no rich results possible in Google.
- Article pages: `Article` schema with author, datePublished, dateModified
- Home page: `WebSite` schema with SearchAction
- Static pages: `WebPage`, `AboutPage`, `ContactPage`, `CollectionPage`

### 6. Missing robots meta (ALL pages)
Added `index, follow` to all indexable pages.
Added `noindex, follow` to legal pages (privacy, terms, disclaimer, cookie policy).

---

## ✅ SEO Improvements

- Canonical URLs on all 20 pages
- Open Graph tags on all 20 pages
- Twitter Card tags on all 20 pages
- JSON-LD schema on all 20 pages
- `meta name="author"` on all pages
- Improved `og:title` descriptions on article pages
- `og:locale` set to `en_IN`
- `og:site_name` set on all pages

---

## 💰 AdSense Integration

**⚠️ ACTION REQUIRED:** Replace placeholder values before going live:
1. Replace `ca-pub-XXXXXXXXXXXXXXXXX` with your actual AdSense Publisher ID
2. Replace `YYYYYYYYYY` with your actual Ad Slot ID (in-content banner)
3. Replace `ZZZZZZZZZZ` with your actual Ad Slot ID (mid-article)

You can find these in your Google AdSense dashboard under:
Ads → By ad unit → Display ads

### What was added:
- AdSense `<script>` tag in `<head>` of all 20 pages
- 2 × responsive ad unit placeholders in each article page (7 articles)
- 1 × responsive ad unit placeholder on the homepage

---

## 📋 What to do in GitHub

1. Replace all `.html` files with the ones from this folder
2. Replace `css/style.css` with the one from this folder
3. Update `ca-pub-XXXXXXXXXXXXXXXXX` with your real AdSense publisher ID
4. Update ad slot IDs (`YYYYYYYYYY`, `ZZZZZZZZZZ`) with real slot IDs
5. Submit updated sitemap to Google Search Console
