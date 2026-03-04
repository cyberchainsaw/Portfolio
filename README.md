# Cybersecurity Portfolio (Static)

This is a **static** (HTML/CSS only) cybersecurity-themed portfolio site with subtle CSS animations.

## Files
- `index.html` — main page
- `styles.css` — custom theme + animations
- `assets/` — place your images here (4 placeholders included)

## How to use
1. Open `index.html` in your browser (double-click).
2. Customize text:
   - Replace `Your Name`, links, and content in each section.
3. Add your images:
   - Put images into `assets/` and update the `<img src="assets/...">` paths in `index.html`.

## Secure hosting tips (recommended)
If you host this (GitHub Pages, Netlify, etc.), add these HTTP headers if your host supports it:

**Content-Security-Policy (CSP)** (example; adjust if you add external resources):
- `default-src 'self'; img-src 'self' https: data:; style-src 'self' https://cdn.jsdelivr.net; base-uri 'self'; form-action 'self'; frame-ancestors 'none'; upgrade-insecure-requests`

Other helpful headers:
- `X-Content-Type-Options: nosniff`
- `Referrer-Policy: no-referrer`
- `X-Frame-Options: DENY`
- `Permissions-Policy: camera=(), microphone=(), geolocation=()`

Notes:
- The contact/subscribe forms are **disabled** (they don't submit anywhere). This avoids collecting data unintentionally.
- No JavaScript is used.

## Customize the brand
In `index.html`, update:
- Site title
- Navbar brand
- Contact links

Enjoy!
