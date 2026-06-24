# Taropa Studios — website

Static site for **taropastudios.com**.

## Local preview

Open `index.html` in a browser. No build step. Pure HTML + CSS.

## Deploy

Pushed to GitHub → auto-deployed by Cloudflare Pages → served on `taropastudios.com`.

## Files

- `index.html` — landing page (dark studio theme: hero, about, expertise, projects, contact)
- `privacy.html` — site-wide Privacy Policy (GDPR-aligned)
- `terms.html` — Terms of Service
- `styles.css` — single stylesheet
- `app-privacy-template.html` — per-app privacy policy template for Google Play / App Store
- `robots.txt`, `sitemap.xml` — SEO

## Editing

Change copy directly in the HTML files. Keep the legal footer block in sync across
all pages (legal name, CUI, registration number, address, email).

### Adding a published app

1. Add a project card in the `#projects` section of `index.html` (replace a placeholder
   card; enable its store badges with real links).
2. Copy `app-privacy-template.html` to `apps/<app-slug>/privacy.html`, fill in the
   placeholders, and ensure it matches the app's Play Console Data Safety form.
3. Add the new privacy URL to `sitemap.xml`.
