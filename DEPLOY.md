# Schedwon — Cloudflare Pages / GitHub Ready

This folder is a static HTML/CSS/JS website and is ready to publish from the repository root.

## Cloudflare Pages settings
- Production branch: main
- Framework preset: None
- Build command: leave blank (or use `exit 0`)
- Build output directory: `/` (repository root)
- `index.html` is at the repository root

## GitHub Pages
Publish from the `main` branch, root (`/`).

## Custom domain
After Cloudflare Pages deploys, use:
Project → Custom domains → Set up a domain → `schedwon.com`

If `schedwon.com` is registered elsewhere, Cloudflare will show the DNS/nameserver steps required for the custom domain.

## Important before launch
- Review `privacy.html` and `terms.html` with your legal/business details.
- Confirm the sales/contact email used by the contact form.
- Replace any placeholder business details, claims, integrations, testimonials, pricing, or social links before publishing.
- Test every navigation link and the contact form after deployment.

## Repository structure
- `index.html` — homepage
- Product pages: `crm.html`, `prm.html`
- Service pages under the root
- `assets/` — shared CSS/assets
- `privacy.html`, `terms.html`, `404.html`
- `robots.txt`, `sitemap.xml`
