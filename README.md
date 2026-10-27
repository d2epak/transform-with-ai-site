# transform-with.ai site

Static site for GitHub Pages. No build step, no JavaScript, no third-party requests.

Files: index.html, 404.html, CNAME (custom domain), .nojekyll.

Before publishing, replace [COMPANY NUMBER] and [REGISTERED OFFICE ADDRESS] in the footer of index.html.

Preview: python3 -m http.server 8000, then open http://localhost:8000

DNS (Namecheap, Advanced DNS) for the apex and www:
A  @    185.199.108.153
A  @    185.199.109.153
A  @    185.199.110.153
A  @    185.199.111.153
CNAME www <github-username>.github.io
Keep the existing MX, SPF, Brevo DKIM and DMARC records unchanged.
