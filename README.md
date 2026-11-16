# Christopher A. Wheeler, RN — résumé website

Static mobile-friendly professional résumé website.

## Files
- `index.html` — complete static site
- `assets/Christopher_Wheeler_Resume.pdf` — downloadable résumé PDF

## Coolify deployment
- Build strategy: Nixpacks/Railpack static site
- Publish directory: `/`
- Web server: nginx:alpine
- Domain: `christopherawheeler.net` and `www.christopherawheeler.net`
- Internal port: 80

Use the existing Coolify GitHub source and deploy from `main`. Keep existing Fastmail DNS records unchanged. The Cloudflare apex A record already points to the Coolify server IP shown by Coolify's generated sslip.io hostname.
