# CapitalK Investment Private Limited — Website

Static institutional-style website for CapitalK Investment Private Limited.

## Recommended hosting: Cloudflare Pages

Cloudflare Pages supports static HTML sites directly. Connect this repository to Cloudflare Pages.

- Framework preset: none / static HTML
- Build command: exit 0 (or leave blank where supported)
- Build output directory: .
- Production branch: main

After deployment, attach the final custom domain in Cloudflare.

## Alternative: Vercel

Import the repository into Vercel as a static project. No build step is required. The included vercel.json adds basic security headers.

## Before launch

1. Replace YOUR-DOMAIN.example in robots.txt and sitemap.xml with the final domain.
2. Confirm legal/disclaimer language with the company's legal/tax adviser.
3. Add the final domain to the Substack/company links if needed.
4. If desired, enable Cloudflare Web Analytics after deployment.
5. Test mobile navigation, mailto link, Substack links, 404 page and favicon.

## Files

- index.html — main website
- styles.css — styling
- logo.svg — provisional CapitalK logo
- 404.html — custom not-found page
- robots.txt — crawler instructions
- sitemap.xml — sitemap placeholder
- _headers — Cloudflare security headers
- vercel.json — Vercel security headers
